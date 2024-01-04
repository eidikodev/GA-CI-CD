<div>
    <div v-if="hasError" class="uk-alert-danger" uk-alert>
      <a class="uk-alert-close" uk-close></a>
      <p v-html="error"></p>
