<template>
  <NucGridPage v-bind:gap="{'col':0,'row':0}" v-bind:rows="[1]"
    v-bind:schema="{'r0-c0':{'col':0,'row':0,'showIn':['xs','sm','md','lg'],'colSpan':1,'rowSpan':1}}"
    v-bind:columns="[1]" overflow="auto" v-bind:designMode="false" v-bind:minNsLimit="300"
    v-bind:style="{'background':'#FFFFFF','paddingTop':'0px','paddingLeft':'0px','paddingRight':'0px','paddingBottom':'0px'}">
    <NucGridCell v-bind:wrap="true" v-bind:reverse="false" overflow="hidden" direction="column"
      v-bind:showInDevice="['xs','sm','md','lg']" verticalAlignment="top" horizontalAlignment="left"
      id="271dddc7-4897-4ff0-a448-2b34a5bd6d47" v-bind:col="0" v-bind:row="0" v-bind:colSpan="1" v-bind:rowSpan="1"
      v-bind:marginTop="0" v-bind:marginLeft="0" v-bind:marginRight="0" v-bind:marginBottom="0"
      v-bind:style="{'background':'transparent','paddingTop':'0px','borderColor':'','borderStyle':'solid','borderWidth':'0px','paddingLeft':'0px','borderRadius':'0px','paddingRight':'0px','paddingBottom':'0px','borderTopWidth':'0px','borderLeftWidth':'0px','borderRightWidth':'0px','borderBottomWidth':'0px','borderTopLeftRadius':'1px','borderTopRightRadius':'1px','borderBottomLeftRadius':'1px','borderBottomRightRadius':'1px'}"
      slot="r0-c0" area="r0-c0">
      <NucGroupElement top="12.309368191721132%" left="12.123397435897436%" v-bind:snapX="false" v-bind:snapY="false"
        bgColor="" position="absolute" v-bind:visibility="true" ncTooltipText="" nucalScaleWidth="0.382"
        nucalScaleHeight="0.523" id="0e5dde20-be4d-4108-8bf6-3dff00f0f1ed"
        v-bind:style="{'color':'#FFFFFF','fontSize':'15px','maxWidth':'','minWidth':'','tabIndex':'-1','fontStyle':'normal','marginTop':'0px','maxHeight':'','minHeight':'','textAlign':'center','background':'','fontFamily':'Roboto-Regular,Roboto','fontWeight':'normal','lineHeight':'1.25','marginLeft':'0px','paddingTop':'5px','textShadow':'','marginRight':'0px','paddingLeft':'6px','marginBottom':'0px','paddingRight':'6px','paddingBottom':'5px','textDecoration':'none'}">
        <WSquaredPrimaryButton tag="button" top="16.038012171705667%" left="19.229270923856042%" v-bind:pill="false"
          size="md" text="Primary" type="button" v-bind:block="false" color="" v-bind:snapX="false" v-bind:snapY="false"
          theme="theme--light01" v-bind:squared="true" variant="primary" position="absolute" v-bind:isEnabled="true"
          background="" borderColor="" ncTypography="body1" v-bind:resetTrigger="false" ncTooltipText=""
          verticalWidth="60px"
          v-bind:nucalDataModel="{'type':'NSW','isList':false,'dynamic':false,'structure':[{'type':'string','propName':'text','displayName':'Value'}]}"
          verticalHeight="60px" horizontalWidth="72.4479px" nucalScaleWidth="" horizontalHeight="37.5347px"
          ncClickFontColor="#FFFFFF" ncFocusFontColor="#FFFFFF" ncHoverFontColor="#FFFFFF" nucalScaleHeight=""
          ncClickBorderColor="#4285f4" ncDisableFontColor="#FFFFFF" ncFocusBorderColor="#4285f4"
          ncHoverBorderColor="#4285f4" ncDisableBorderColor="transparent" ncClickBackgroundColor="#4285f4"
          ncFocusBackgroundColor="#4285f4" ncHoverBackgroundColor="#4285f4" ncDisableBackgroundColor="#969696"
          id="a453b1bd-d6ee-4962-a119-29f7dfb2d58a"
          v-bind:style="{'width':'','height':'','fontSize':'12px','maxWidth':'','minWidth':'','tabIndex':'0px','boxShadow':'','fontStyle':'normal','marginTop':'0px','maxHeight':'','minHeight':'','textAlign':'center','fontFamily':'OpenSans-Bold,Open Sans','fontWeight':'bold','lineHeight':'1.4','marginLeft':'0px','paddingTop':'','textShadow':'','visibility':'visible','borderStyle':'solid','marginRight':'0px','paddingLeft':'','marginBottom':'0px','paddingRight':'','paddingBottom':'','borderTopWidth':'1px','textDecoration':'none','borderLeftWidth':'1px','borderRightWidth':'1px','horizontalHeight':'37.5347px','borderBottomWidth':'1px','borderTopLeftRadius':'4px','borderTopRightRadius':'4px','borderBottomLeftRadius':'4px','borderBottomRightRadius':'4px'}"/>
        <WDefaultCheckbox top="5.962183096299671%" left="14.434688801654131%" size="md"
          label="I accept the terms and use" v-bind:plain="false" v-bind:snapX="false" v-bind:snapY="false"
          theme="theme--light01" v-bind:value="true" v-bind:inline="false" fontSize="14px" position="absolute"
          v-bind:autofocus="false" v-bind:isEnabled="true" textAlign="left" fontFamily="Roboto-Regular,Roboto"
          fontWeight="normal" ncTypography="custom" v-bind:indeterminate="false" labelPosition="right" ncTooltipText=""
          v-bind:checkboxSwitch="false"
          v-bind:nucalDataModel="{'type':'NSW','isList':false,'dynamic':false,'structure':[{'type':'boolean','propName':'value','displayName':'Value'},{'type':'string','propName':'label','displayName':'Display'}]}"
          nucalScaleWidth="" ncFocusFontColor="black" ncHoverFontColor="black" nucalScaleHeight=""
          ncDisableFontColor="black" ncFocusBorderColor="black" ncHoverBorderColor="black" ncDisableBorderColor="black"
          ncFocusBackgroundColor="transparent" ncHoverBackgroundColor="transparent"
          ncDisableBackgroundColor="transparent" id="2f300b26-e645-44fa-b094-1ba2db633c22"
          v-bind:style="{'color':'','maxWidth':'','minWidth':'','tabIndex':'0px','boxShadow':'','fontStyle':'none','marginTop':'0px','maxHeight':'','minHeight':'','lineHeight':'','marginLeft':'0px','paddingTop':'0px','textShadow':'','visibility':'visible','marginRight':'0px','paddingLeft':'0px','marginBottom':'0px','paddingRight':'0px','paddingBottom':'0px','textDecoration':'none'}"/>
        <NucDataTable top="35.74706284375305%" left="9.256540109676067%" v-bind:list="[]" type="" v-bind:snapX="false"
          v-bind:snapY="false" theme="theme--light01" v-bind:columns="[]" parject="" position="absolute" dataModel=""
          bindMethod="function" v-bind:extensions="{}" ncTypography="body2" v-bind:selectedRows="[]"
          v-bind:nucalDataModel="{'type':'NSW','isList':true,'update':{'dataModel':'dataModel'},'dynamic':true,'dataModel':'','structure':[{'type':'ids-list','update':{'dataModel':'dataModel'},'propName':'selectedRows','dataModel':'','displayName':'SelectedRows'},{'type':'ids-list','update':{'dataModel':'dataModel'},'propName':'list','dataModel':'','displayName':'List'}]}"
          nucalScaleWidth="" nucalScaleHeight="" v-bind:specialEventList="[]" id="9b003ccb-e7fc-488a-be0f-54045bd92d35"
          v-bind:style="{'color':'#475562','fontSize':'11px','maxWidth':'','minWidth':'300px','fontStyle':'normal','marginTop':'0px','maxHeight':'','minHeight':'100px','textAlign':'left','fontFamily':'Roboto-Regular,Roboto','fontWeight':'normal','marginLeft':'0px','paddingTop':'12px','visibility':'visible','marginRight':'0px','paddingLeft':'13px','marginBottom':'0px','paddingRight':'13px','paddingBottom':'12px','textDecoration':'none'}"/>
      </NucGroupElement>
      <NucGroupElement top="12.527233115468409%" left="54.21245421245421%" v-bind:snapX="false" v-bind:snapY="false"
        bgColor="" position="absolute" v-bind:visibility="true" ncTooltipText="" nucalScaleWidth="0.382"
        nucalScaleHeight="0.523" id="256e934a-ac6c-4688-8a9e-5cbe7bcb887b"
        v-bind:style="{'color':'#FFFFFF','fontSize':'15px','maxWidth':'','minWidth':'','tabIndex':'-1','fontStyle':'normal','marginTop':'0px','maxHeight':'','minHeight':'','textAlign':'center','background':'','fontFamily':'Roboto-Regular,Roboto','fontWeight':'normal','lineHeight':'1.25','marginLeft':'0px','paddingTop':'5px','textShadow':'','marginRight':'0px','paddingLeft':'6px','marginBottom':'0px','paddingRight':'6px','paddingBottom':'5px','textDecoration':'none'}">
        <WSquaredPrimaryButton tag="button" top="16.038012171705667%" left="19.229270923856042%" v-bind:pill="false"
          size="md" text="Primary" type="button" v-bind:block="false" color="" v-bind:snapX="false" v-bind:snapY="false"
          theme="theme--light01" v-bind:squared="true" variant="primary" position="absolute" v-bind:isEnabled="true"
          background="" borderColor="" ncTypography="body1" v-bind:resetTrigger="false" ncTooltipText=""
          verticalWidth="60px"
          v-bind:nucalDataModel="{'type':'NSW','isList':false,'dynamic':false,'structure':[{'type':'string','propName':'text','displayName':'Value'}]}"
          verticalHeight="60px" horizontalWidth="72.4479px" nucalScaleWidth="" horizontalHeight="37.5347px"
          ncClickFontColor="#FFFFFF" ncFocusFontColor="#FFFFFF" ncHoverFontColor="#FFFFFF" nucalScaleHeight=""
          ncClickBorderColor="#4285f4" ncDisableFontColor="#FFFFFF" ncFocusBorderColor="#4285f4"
          ncHoverBorderColor="#4285f4" ncDisableBorderColor="transparent" ncClickBackgroundColor="#4285f4"
          ncFocusBackgroundColor="#4285f4" ncHoverBackgroundColor="#4285f4" ncDisableBackgroundColor="#969696"
          id="658ea133-f1a2-435a-9087-939c1833df36"
          v-bind:style="{'width':'','height':'','fontSize':'12px','maxWidth':'','minWidth':'','tabIndex':'0px','boxShadow':'','fontStyle':'normal','marginTop':'0px','maxHeight':'','minHeight':'','textAlign':'center','fontFamily':'OpenSans-Bold,Open Sans','fontWeight':'bold','lineHeight':'1.4','marginLeft':'0px','paddingTop':'','textShadow':'','visibility':'visible','borderStyle':'solid','marginRight':'0px','paddingLeft':'','marginBottom':'0px','paddingRight':'','paddingBottom':'','borderTopWidth':'1px','textDecoration':'none','borderLeftWidth':'1px','borderRightWidth':'1px','horizontalHeight':'37.5347px','borderBottomWidth':'1px','borderTopLeftRadius':'4px','borderTopRightRadius':'4px','borderBottomLeftRadius':'4px','borderBottomRightRadius':'4px'}"/>
        <WDefaultCheckbox top="5.962183096299671%" left="14.434688801654131%" size="md"
          label="I accept the terms and use" v-bind:plain="false" v-bind:snapX="false" v-bind:snapY="false"
          theme="theme--light01" v-bind:value="true" v-bind:inline="false" fontSize="14px" position="absolute"
          v-bind:autofocus="false" v-bind:isEnabled="true" textAlign="left" fontFamily="Roboto-Regular,Roboto"
          fontWeight="normal" ncTypography="custom" v-bind:indeterminate="false" labelPosition="right" ncTooltipText=""
          v-bind:checkboxSwitch="false"
          v-bind:nucalDataModel="{'type':'NSW','isList':false,'dynamic':false,'structure':[{'type':'boolean','propName':'value','displayName':'Value'},{'type':'string','propName':'label','displayName':'Display'}]}"
          nucalScaleWidth="" ncFocusFontColor="black" ncHoverFontColor="black" nucalScaleHeight=""
          ncDisableFontColor="black" ncFocusBorderColor="black" ncHoverBorderColor="black" ncDisableBorderColor="black"
          ncFocusBackgroundColor="transparent" ncHoverBackgroundColor="transparent"
          ncDisableBackgroundColor="transparent" id="3f7d4859-91c5-4fca-ab19-84a7a4ac6301"
          v-bind:style="{'color':'','maxWidth':'','minWidth':'','tabIndex':'0px','boxShadow':'','fontStyle':'none','marginTop':'0px','maxHeight':'','minHeight':'','lineHeight':'','marginLeft':'0px','paddingTop':'0px','textShadow':'','visibility':'visible','marginRight':'0px','paddingLeft':'0px','marginBottom':'0px','paddingRight':'0px','paddingBottom':'0px','textDecoration':'none'}"/>
        <NucDataTable top="35.74706284375305%" left="9.256540109676067%" v-bind:list="[]" type="" v-bind:snapX="false"
          v-bind:snapY="false" theme="theme--light01" v-bind:columns="[]" parject="" position="absolute" dataModel=""
          bindMethod="function" v-bind:extensions="{}" ncTypography="body2" v-bind:selectedRows="[]"
          v-bind:nucalDataModel="{'type':'NSW','isList':true,'update':{'dataModel':'dataModel'},'dynamic':true,'dataModel':'','structure':[{'type':'ids-list','update':{'dataModel':'dataModel'},'propName':'selectedRows','dataModel':'','displayName':'SelectedRows'},{'type':'ids-list','update':{'dataModel':'dataModel'},'propName':'list','dataModel':'','displayName':'List'}]}"
          nucalScaleWidth="" nucalScaleHeight="" v-bind:specialEventList="[]" id="375aec7e-fad8-4c52-a56e-5fd5bbf10725"
          v-bind:style="{'color':'#475562','fontSize':'11px','maxWidth':'','minWidth':'300px','fontStyle':'normal','marginTop':'0px','maxHeight':'','minHeight':'100px','textAlign':'left','fontFamily':'Roboto-Regular,Roboto','fontWeight':'normal','marginLeft':'0px','paddingTop':'12px','visibility':'visible','marginRight':'0px','paddingLeft':'13px','marginBottom':'0px','paddingRight':'13px','paddingBottom':'12px','textDecoration':'none'}"/>
      </NucGroupElement>
    </NucGridCell>
  </NucGridPage>
</template>
<script>
export default {
  name: 'Screen3',
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