<template>
  <div class="container d-none d-sm-block">
    <ul class="nav nav-tabs" role="tablist" id="tab-parent">
      <li class="nav-item" role="presentation" v-for="(item, index) in data" :key="index">
        <button class="nav-link" :class="index == 0 ? 'active' : ''" :id="'tab' + index" type="button" data-bs-toggle="tab" :data-bs-target="'#pane' + index" :aria-selected="index == 0 ? true : false" :aria-controls="'pane' + index" aria-current="page">{{ item.title }}</button>
      </li>
    </ul>
    <div class="tab-content" v-for="(item, index) in data" :key="index">
      <div class="tab-pane fade text-start" :class="index == 0 ? 'show active' : ''" :id="'pane' + index" role="tabpanel" :aria-labelledby="'tab' + index" v-html="item.content"></div>
    </div>
  </div>
  <div class="container d-md-none">
    <div class="accordion" id="accordion-parent">
      <div class="accordion-item" v-for="(item, index) in data" :key="index">
        <h3 class="accordion-header" :id="'header' + index">
          <button class="accordion-button" :class="index != 0 ? 'collapsed' : ''" type="button" data-bs-toggle="collapse" :data-bs-target="'#body' + index" :aria-expanded="index == 0 ? true : false" :aria-controls="'body' + index">{{ item.title }}</button>
        </h3>
        <div class="accordion-collapse collapse" :class="index == 0 ? 'show' : ''" :id="'body' + index" :aria-labelledby="'header' + index" data-bs-parent="#accordion-parent">
          <div class="accordion-body text-start">
            <div v-html="item.content"></div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'PageContent',
  props: ['data']
}
</script>
