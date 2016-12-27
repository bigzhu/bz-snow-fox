<template>
  <div>
    <doc :name="name"
      :desc="desc"
      :parm_desc="parm_desc"
      :parms="parms"
      :code="code"
      >
    </doc>
    <bz></bz>
  </div>
</template>
<script>
  // import toastr from 'toastr'

  import Bz from './Bz'
  import Doc from 'bz-doc'
  export default {
    components: {
      Bz,
      Doc
    },
    data: function () {
      return {
        loading: false,
        name: 'bz-snow-fox',
        desc: '狐狸',
        parms: [
          {parm: '', desc: ''}
        ],
        parm_desc: ``,
        code: `<bz></bz>`
      }
    },
    methods: {
    }
  }
</script>
