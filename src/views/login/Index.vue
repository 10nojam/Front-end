<script>
  // Extensions
  import View from '@/views/View'

  // Mixins
  import LoadSections from '@/mixins/load-sections'
  export default {
    name: 'login',
    metaInfo: { title: 'Login' },
    extends: View,
    mixins: [
        LoadSections([
          'login',
      ]),
    ],
    props: {
      id: {
        type: String,
        default: 'login',
      },
    }
  }
</script>