<template>
  <div class="md-example-child md-example-child-icon md-example-child-icon-0">
    <div
      class="md-example-item"
      v-for="icon in iconList"
      :key="icon"
    >
      <md-icon
        :name="icon.split('/')[0]"
        size="lg"
      ></md-icon>
      <p>{{ icon }}</p>
    </div>
  </div>
</template>

<script>import {Icon} from 'mand-mobile'

export default {
  name: 'icon-demo',
  /* DELETE */
  title: '字体图标',
  titleEnUS: 'Icon Font',
  align: 'center',
  background: '#fff',
  /* DELETE */
  components: {
    [Icon.name]: Icon,
  },
  data() {
    return {
      iconList: [
        'square-checked',
        'square-check',
        'rectangle',
        'right',
        'wrong',
        'arrow',
        'arrow-left',
        'arrow-right',
        'arrow-up',
        'arrow-down',
        'invisible',
        'visible',
        'service',
        'setting',
        'close',
        'refresh',
        'edit',
        'sort',
        'info',
        'question',
        'security',
        'rmb',
        'wait',
        'check',
        'checked/success',
        'check-disabled',
        'clear/fail',
        'warn',
        'info-solid',
        'scan',
        'share',
        'back',
        'card-bag',
        'message',
        'order',
        'balance',
        'coupon',
        'address-book',
        'mobile-phone',
        'calendar',
        'home',
        'discovery',
        'switch',
        'time',
        'search',
        'user',
        'camera',
        'clock',
        'delete',
        'profession',
        'id-card',
        'authentication',
        'location',
        'filter',
        'motor-vehicle',
        'phone',
        'volumn',
      ],
    }
  },
}
</script>
