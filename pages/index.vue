<template>
  <div>
    <div class="purple-header">
      <b-navbar toggleable="md" type="dark">
        <b-navbar-brand href="#">TheMetaDB</b-navbar-brand>

        <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

        <b-collapse id="nav-collapse" is-nav>
          <b-navbar-nav>
            <b-nav-item href="#">Browse</b-nav-item>
            <b-nav-item href="#">Contribute</b-nav-item>
            <b-nav-item href="#">Documentation</b-nav-item>
          </b-navbar-nav>
        </b-collapse>

        <b-navbar-nav class="ml-auto">
          <b-nav-item href="#">Register</b-nav-item>
          <b-nav-item href="#">Sign in</b-nav-item>
        </b-navbar-nav>
      </b-navbar>

      <b-container class="mt-5">
        <b-row class="mb-4">
          <b-col class="text-center">
            <h1 class="h2 text-light font-weight-light">
              Open metadata for everyone
            </h1>
          </b-col>
        </b-row>
        <b-row class="justify-content-center">
          <b-col class="col-6">
            <b-form-input
              type="text"
              size="lg"
              placeholder="Search"
              class="rounded-input"
            ></b-form-input>
          </b-col>
        </b-row>
        <b-row class="mt-5 justify-content-center">
          <b-col class="col-3 flex-column text-light text-center">
            <div class="icons-header font-weight-bold">
              Provides metadata for
            </div>
          </b-col>
        </b-row>
        <b-col class="flex-column text-light text-center">
          <b-row class="mt-3 justify-content-center icons">
            <img src="/icon-transparent-white.svg" />
          </b-row>
        </b-col>
      </b-container>
    </div>
    <b-container class="mt-4">
      <b-row>
        <b-col>
          <h2 class="h4 mb-4">Recently updated</h2>
          <div class="list-group">
            <a href="#" class="list-group-item list-group-item-action">
              <div class="d-flex">
                <div>
                  <img src="/poster-placeholder.webp" />
                </div>
                <div class="ml-2 d-flex flex-column align-items-start">
                  <div class="font-weight-bold">Cras justo odio</div>
                  <div class="mb-auto">
                    Lorem ipsum dolor sit amet, consectetur adipiscing elit.
                    Nullam rutrum nisl nulla, eu placerat lacus ornare ut. Proin
                    varius tortor arcu. Aliquam lobortis tristique arcu.
                  </div>
                  <small>Donec id elit non mi porta.</small>
                </div>
              </div>
            </a>
            <a href="#" class="list-group-item list-group-item-action">
              <div class="d-flex">
                <div>
                  <img src="/poster-placeholder.webp" />
                </div>
                <div class="ml-2 d-flex flex-column align-items-start">
                  <div class="font-weight-bold">Cras justo odio</div>
                  <div class="mb-auto">
                    Lorem ipsum dolor sit amet, consectetur adipiscing elit.
                    Nullam rutrum nisl nulla, eu placerat lacus ornare ut. Proin
                    varius tortor arcu. Aliquam lobortis tristique arcu.
                  </div>
                  <small>Donec id elit non mi porta.</small>
                </div>
              </div>
            </a>
            <a href="#" class="list-group-item list-group-item-action">
              <div class="d-flex">
                <div>
                  <img src="/poster-placeholder.webp" />
                </div>
                <div class="ml-2 d-flex flex-column align-items-start">
                  <div class="font-weight-bold">Cras justo odio</div>
                  <div class="mb-auto">
                    Lorem ipsum dolor sit amet, consectetur adipiscing elit.
                    Nullam rutrum nisl nulla, eu placerat lacus ornare ut. Proin
                    varius tortor arcu. Aliquam lobortis tristique arcu.
                  </div>
                  <small>Donec id elit non mi porta.</small>
                </div>
              </div>
            </a>
            <a href="#" class="list-group-item list-group-item-action">
              <div class="d-flex">
                <div>
                  <img src="/poster-placeholder.webp" />
                </div>
                <div class="ml-2 d-flex flex-column align-items-start">
                  <div class="font-weight-bold">Cras justo odio</div>
                  <div class="mb-auto">
                    Lorem ipsum dolor sit amet, consectetur adipiscing elit.
                    Nullam rutrum nisl nulla, eu placerat lacus ornare ut. Proin
                    varius tortor arcu. Aliquam lobortis tristique arcu.
                  </div>
                  <small>Donec id elit non mi porta.</small>
                </div>
              </div>
            </a>
            <a href="#" class="list-group-item list-group-item-action">
              <div class="d-flex">
                <div>
                  <img src="/poster-placeholder.webp" />
                </div>
                <div class="ml-2 d-flex flex-column align-items-start">
                  <div class="font-weight-bold">Cras justo odio</div>
                  <div class="mb-auto">
                    Lorem ipsum dolor sit amet, consectetur adipiscing elit.
                    Nullam rutrum nisl nulla, eu placerat lacus ornare ut. Proin
                    varius tortor arcu. Aliquam lobortis tristique arcu.
                  </div>
                  <small>Donec id elit non mi porta.</small>
                </div>
              </div>
            </a>
          </div>
        </b-col>
        <b-col>
          <h2 class="h4 mb-4">Recently added</h2>
          <div class="list-group">
            <a href="#" class="list-group-item list-group-item-action">
              <div class="d-flex">
                <div>
                  <img src="/poster-placeholder.webp" />
                </div>
                <div class="ml-2 d-flex flex-column align-items-start">
                  <div class="font-weight-bold">Cras justo odio</div>
                  <div class="mb-auto">
                    Lorem ipsum dolor sit amet, consectetur adipiscing elit.
                    Nullam rutrum nisl nulla, eu placerat lacus ornare ut. Proin
                    varius tortor arcu. Aliquam lobortis tristique arcu.
                  </div>
                  <small>Donec id elit non mi porta.</small>
                </div>
              </div>
            </a>
            <a href="#" class="list-group-item list-group-item-action">
              <div class="d-flex">
                <div>
                  <img src="/poster-placeholder.webp" />
                </div>
                <div class="ml-2 d-flex flex-column align-items-start">
                  <div class="font-weight-bold">Cras justo odio</div>
                  <div class="mb-auto">
                    Lorem ipsum dolor sit amet, consectetur adipiscing elit.
                    Nullam rutrum nisl nulla, eu placerat lacus ornare ut. Proin
                    varius tortor arcu. Aliquam lobortis tristique arcu.
                  </div>
                  <small>Donec id elit non mi porta.</small>
                </div>
              </div>
            </a>
            <a href="#" class="list-group-item list-group-item-action">
              <div class="d-flex">
                <div>
                  <img src="/poster-placeholder.webp" />
                </div>
                <div class="ml-2 d-flex flex-column align-items-start">
                  <div class="font-weight-bold">Cras justo odio</div>
                  <div class="mb-auto">
                    Lorem ipsum dolor sit amet, consectetur adipiscing elit.
                    Nullam rutrum nisl nulla, eu placerat lacus ornare ut. Proin
                    varius tortor arcu. Aliquam lobortis tristique arcu.
                  </div>
                  <small>Donec id elit non mi porta.</small>
                </div>
              </div>
            </a>
            <a href="#" class="list-group-item list-group-item-action">
              <div class="d-flex">
                <div>
                  <img src="/poster-placeholder.webp" />
                </div>
                <div class="ml-2 d-flex flex-column align-items-start">
                  <div class="font-weight-bold">Cras justo odio</div>
                  <div class="mb-auto">
                    Lorem ipsum dolor sit amet, consectetur adipiscing elit.
                    Nullam rutrum nisl nulla, eu placerat lacus ornare ut. Proin
                    varius tortor arcu. Aliquam lobortis tristique arcu.
                  </div>
                  <small>Donec id elit non mi porta.</small>
                </div>
              </div>
            </a>
            <a href="#" class="list-group-item list-group-item-action">
              <div class="d-flex">
                <div>
                  <img src="/poster-placeholder.webp" />
                </div>
                <div class="ml-2 d-flex flex-column align-items-start">
                  <div class="font-weight-bold">Cras justo odio</div>
                  <div class="mb-auto">
                    Lorem ipsum dolor sit amet, consectetur adipiscing elit.
                    Nullam rutrum nisl nulla, eu placerat lacus ornare ut. Proin
                    varius tortor arcu. Aliquam lobortis tristique arcu.
                  </div>
                  <small>Donec id elit non mi porta.</small>
                </div>
              </div>
            </a>
          </div>
        </b-col>
      </b-row>
    </b-container>
    <footer class="mt-4 pt-5 pb-5">
      <b-container>
        <b-row>
          <b-col class="col-3">
            <h1 class="h3 font-weight-bold">TheMetaDB</h1>
          </b-col>
          <b-col class="col-6">
            <h3>Contribute</h3>
            <ul>
              <li><a href="#">Read the documentation</a></li>
              <li><a href="#">Fork on Github</a></li>
            </ul>
          </b-col>
        </b-row>
      </b-container>
    </footer>
  </div>
</template>

<script lang="ts">
import Vue from 'vue'

export default Vue.extend({})
</script>

<style lang="scss" scoped>
.purple-header {
  background: linear-gradient(135deg, #201850, #7a3b8f);
  background-color: #184e8e;
  padding-bottom: 80px;
  font-family: 'Source Sans Pro', sans-serif;
}
.rounded-input {
  border-radius: 1.25em;
}
.icons-header {
  text-transform: uppercase;
  &::before,
  &::after {
    background-color: rgba(255, 255, 255, 0.4);
    content: '';
    height: 1px;
    left: -60px;
    position: absolute;
    top: 50%;
    width: 50px;
  }
  &::after {
    left: auto;
    right: -60px;
  }
}
.icons {
  img {
    width: 4em;
    height: 4em;
  }
}
footer {
  background-color: #333c44;
  color: #f0f9ff;

  h3 {
    margin-top: 0;
    margin-bottom: 12px;
    font-weight: bold;
    font-size: 16px;
  }
  ul {
    padding: 0;
    list-style: none;
    line-height: 1.6;
    font-size: 14px;
    margin-bottom: 0;
  }

  ul a {
    color: inherit;
    text-decoration: none;
    opacity: 0.6;
  }

  ul a:hover {
    opacity: 0.8;
  }
}
</style>
