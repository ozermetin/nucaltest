<template>
  <NucSide v-bind:gap="{'col':0,'row':0}" logo="" v-bind:rows="[1]"
    v-bind:items="[{'id':'24a57581-2ee3-470f-8314-65e1d5da531a','icon':{'icon':'','library':''},'type':'link','title':'Item 1','target':{'view':'3278c220-64bb-4b21-94d1-7d3c474d50b8','target':'view'}}]"
    title="Header"
    v-bind:footer="{'id':'1003969c-93fc-4919-8dd9-449e472db2d9','icon':{'icon':'','library':''},'type':'link','title':'Footer','target':{'view':'','target':''},'isEmpty':'true','isExcluded':false}"
    v-bind:schema="{'r0-c0':{'col':0,'row':0,'showIn':['xs','sm','md','lg'],'colSpan':1,'rowSpan':1}}"
    v-bind:target="{'page':'','view':'3278c220-64bb-4b21-94d1-7d3c474d50b8','target':'view'}" v-bind:columns="[1,4]"
    current="3278c220-64bb-4b21-94d1-7d3c474d50b8" headerId="bb49cd92-1a92-4af9-aaa9-08ebaec3c9d9" overflow="auto"
    v-bind:designMode="false" v-bind:minNsLimit="250" v-bind:isLogoExcluded="false" v-bind:isTitleExcluded="false"
    v-bind:isFooterExcluded="false" v-bind:isHeaderExcluded="false"
    v-bind:style="{'background':'#FFFFFF','paddingTop':'0px','paddingLeft':'0px','paddingRight':'0px','paddingBottom':'0px'}">
    <NucNavigationDrawer logo=""
      v-bind:items="[{&quot;id&quot;:&quot;24a57581-2ee3-470f-8314-65e1d5da531a&quot;,&quot;icon&quot;:{&quot;icon&quot;:&quot;&quot;,&quot;library&quot;:&quot;&quot;},&quot;type&quot;:&quot;link&quot;,&quot;title&quot;:&quot;Item 1&quot;,&quot;target&quot;:{&quot;view&quot;:&quot;3278c220-64bb-4b21-94d1-7d3c474d50b8&quot;,&quot;target&quot;:&quot;view&quot;}}]"
      title="Header" current="3278c220-64bb-4b21-94d1-7d3c474d50b8" itemActivated="scopedProps.itemActivated"
      v-bind:isLogoExcluded="false" v-bind:isTitleExcluded="false" ncGroupFontSize="11px"
      v-bind:isHeaderExcluded="false" ncHeaderFontSize="16px" ncItemTypography="custom" ncDefaultFontSize="11px"
      ncGroupFontFamily="Roboto-Medium,Roboto" ncGroupTypography="custom" ncHeaderFontFamily="Roboto-Medium,Roboto"
      ncHeaderTypography="custom" ncDefaultFontFamily="Roboto-Medium,Roboto" id="603f5904-316a-407b-9d0d-9a5e7e60b8d3"
      v-bind:col="0" v-bind:row="0"
      v-bind:footer="{&quot;id&quot;:&quot;1003969c-93fc-4919-8dd9-449e472db2d9&quot;,&quot;icon&quot;:{&quot;icon&quot;:&quot;&quot;,&quot;library&quot;:&quot;&quot;},&quot;type&quot;:&quot;link&quot;,&quot;title&quot;:&quot;Footer&quot;,&quot;target&quot;:{&quot;view&quot;:&quot;&quot;,&quot;target&quot;:&quot;&quot;},&quot;isEmpty&quot;:&quot;true&quot;,&quot;isExcluded&quot;:false}"
      v-bind:colSpan="1" v-bind:rowSpan="1" v-bind:style="{}" slot="r0-c0" area="r0-c0"/>
    <NucDynamicView view="scopedProps.view" id="66b2bc57-0934-4a3f-8739-8cc59cb832e1" v-bind:col="0" v-bind:row="0"
      v-bind:colSpan="1" v-bind:rowSpan="1" v-bind:style="{}" slot="r0-c1" area="r0-c1"/>
  </NucSide>
</template>
<script>
export default {
  name: 'Screen1',
  data() {
    return {};
  },
  props: {},
  created() {},
  mounted() {},
  computed: {},
  methods: {},
  watch: {},
};
</script>

<style scoped></style>