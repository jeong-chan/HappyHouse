<template>
  <md-toolbar
    id="toolbar"
    md-elevation="0"
    class="md-white md-absolute"
    :class="extraNavClasses"
  >
    <div class="md-toolbar-row md-collapse-lateral">
      <div class="md-toolbar-section-start">
        <h3 class="md-title">
          <router-link to="/"><b>Happy House</b></router-link>
        </h3>
      </div>
      <div class="md-toolbar-section-end">
        <div class="md-collapse">
          <div class="md-collapse-wrapper">
            <md-list>
              <md-list-item>
                <router-link to="/house">
                  <i class="material-icons">house</i>
                  <p>House</p>
                </router-link>
              </md-list-item>
              <md-list-item
                href="https://demos.creative-tim.com/vue-material-kit/documentation/"
                target="_blank"
              >
                <i class="material-icons">content_paste</i>
                <p>Announcement</p>
              </md-list-item>
              <md-list-item>
                <router-link to="/qna">
                  <i class="material-icons">question_answer</i>
                  <p>QnA</p>
                </router-link>
              </md-list-item>
              <md-list-item>
                <router-link to="/parking">
                  <i class="material-icons">directions_car</i>
                  <p>Parking</p>
                </router-link>
              </md-list-item>
              <li class="md-list-item">
                <a
                  href="javascript:void(0)"
                  class="md-list-item-router md-list-item-container md-button-clean dropdown"
                >
                  <div class="md-list-item-content">
                    <drop-down direction="down">
                      <md-button
                        slot="title"
                        class="md-button md-button-link md-white md-simple dropdown-toggle"
                        data-toggle="dropdown"
                      >
                        <i class="material-icons">account_box</i>
                        <p>User</p>
                      </md-button>
                      <ul
                        class="dropdown-menu dropdown-with-icons"
                        v-if="loginUser.userId"
                      >
                        <li>
                          <a @click="doLogout"
                            ><i class="material-icons">fingerprint</i>
                            <p>Logout</p></a
                          >
                        </li>
                        <li>
                          <router-link to="/user/profile"
                            ><i class="material-icons">account_circle</i>
                            <p>Profile</p>
                          </router-link>
                        </li>
                      </ul>
                      <ul class="dropdown-menu dropdown-with-icons" v-else>
                        <li>
                          <router-link to="/user/login"
                            ><i class="material-icons">fingerprint</i>
                            <p>Login</p></router-link
                          >
                        </li>
                        <li>
                          <router-link to="/user/regist">
                            <i class="material-icons">how_to_reg</i>
                            <p>Regist</p>
                          </router-link>
                        </li>
                      </ul>
                    </drop-down>
                  </div>
                </a>
              </li>
            </md-list>
          </div>
        </div>
      </div>
    </div>
  </md-toolbar>
</template>

<script>
import { mapState, mapActions } from "vuex";

export default {
  components: {},
  props: {
    type: {
      type: String,
      default: "white",
      validator(value) {
        return [
          "white",
          "default",
          "primary",
          "danger",
          "success",
          "warning",
          "info",
        ].includes(value);
      },
    },
  },
  data() {
    return {
      extraNavClasses: "",
    };
  },
  computed: {
    ...mapState(["loginUser"]),
  },
  methods: {
    ...mapActions(["logout"]),
    doLogout() {
      this.logout();
      if (!this.loginUser.userId) {
        this.$router.push("/user/login");
      }
    },
  },
};
</script>
