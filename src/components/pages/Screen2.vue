<template>
  <NucGridPage v-bind:gap="{'col':0,'row':0}" v-bind:rows="[1,1,1,1]"
    v-bind:schema="{'r0-c0':{'col':0,'row':0,'colSpan':1,'rowSpan':1},'r0-c1':{'col':1,'row':0,'colSpan':1,'rowSpan':1},'r0-c2':{'col':2,'row':0,'colSpan':1,'rowSpan':1},'r0-c3':{'col':3,'row':0,'colSpan':1,'rowSpan':1},'r1-c0':{'col':0,'row':1,'colSpan':1,'rowSpan':1},'r1-c1':{'col':1,'row':1,'colSpan':1,'rowSpan':1},'r1-c2':{'col':2,'row':1,'colSpan':1,'rowSpan':1},'r1-c3':{'col':3,'row':1,'colSpan':1,'rowSpan':1},'r2-c0':{'col':0,'row':2,'colSpan':1,'rowSpan':1},'r2-c1':{'col':1,'row':2,'colSpan':1,'rowSpan':1},'r2-c2':{'col':2,'row':2,'colSpan':1,'rowSpan':1},'r2-c3':{'col':3,'row':2,'colSpan':1,'rowSpan':1},'r3-c0':{'col':0,'row':3,'colSpan':1,'rowSpan':1},'r3-c1':{'col':1,'row':3,'colSpan':1,'rowSpan':1},'r3-c2':{'col':2,'row':3,'showIn':['xs','sm','md','lg'],'colSpan':1,'rowSpan':1},'r3-c3':{'col':3,'row':3,'colSpan':1,'rowSpan':1}}"
    v-bind:columns="[1,1,1,1]" overflow="auto" v-bind:designMode="false" v-bind:minNsLimit="300"
    v-bind:style="{'background':'#FFFFFF','paddingTop':'0px','paddingLeft':'0px','paddingRight':'0px','paddingBottom':'0px'}">
    <NucGridCell v-bind:wrap="true" v-bind:reverse="false" overflow="hidden" direction="column"
      v-bind:showInDevice="['xs','sm','md','lg']" verticalAlignment="top" horizontalAlignment="left"
      id="fb6cdf78-3bca-4013-b098-23e5626b18f8" v-bind:col="0" v-bind:row="0" v-bind:colSpan="1" v-bind:rowSpan="1"
      v-bind:marginTop="0" v-bind:marginLeft="0" v-bind:marginRight="0" v-bind:marginBottom="0"
      v-bind:style="{'background':'transparent','paddingTop':'0px','borderColor':'','borderStyle':'solid','borderWidth':'0px','paddingLeft':'0px','borderRadius':'0px','paddingRight':'0px','paddingBottom':'0px','borderTopWidth':'0px','borderLeftWidth':'0px','borderRightWidth':'0px','borderBottomWidth':'0px','borderTopLeftRadius':'1px','borderTopRightRadius':'1px','borderBottomLeftRadius':'1px','borderBottomRightRadius':'1px'}"
      slot="r0-c0" area="r0-c0"/>
    <NucGridCell v-bind:wrap="true" v-bind:reverse="false" overflow="hidden" direction="column"
      v-bind:showInDevice="['xs','sm','md','lg']" verticalAlignment="top" horizontalAlignment="left"
      id="823ae47e-0d3f-4522-840e-c553e3b9febf" v-bind:col="0" v-bind:row="0" v-bind:colSpan="1" v-bind:rowSpan="1"
      v-bind:marginTop="0" v-bind:marginLeft="0" v-bind:marginRight="0" v-bind:marginBottom="0"
      v-bind:style="{'background':'transparent','paddingTop':'0px','borderColor':'','borderStyle':'solid','borderWidth':'0px','paddingLeft':'0px','borderRadius':'0px','paddingRight':'0px','paddingBottom':'0px','borderTopWidth':'0px','borderLeftWidth':'0px','borderRightWidth':'0px','borderBottomWidth':'0px','borderTopLeftRadius':'1px','borderTopRightRadius':'1px','borderBottomLeftRadius':'1px','borderBottomRightRadius':'1px'}"
      slot="r0-c1" area="r0-c1"/>
    <NucGridCell v-bind:wrap="true" v-bind:reverse="false" overflow="hidden" direction="column"
      v-bind:showInDevice="['xs','sm','md','lg']" verticalAlignment="top" horizontalAlignment="left"
      id="bf5c41c5-ce27-4b18-ae2a-b1f68125ff56" v-bind:col="0" v-bind:row="0" v-bind:colSpan="1" v-bind:rowSpan="1"
      v-bind:marginTop="0" v-bind:marginLeft="0" v-bind:marginRight="0" v-bind:marginBottom="0"
      v-bind:style="{'background':'transparent','paddingTop':'0px','borderColor':'','borderStyle':'solid','borderWidth':'0px','paddingLeft':'0px','borderRadius':'0px','paddingRight':'0px','paddingBottom':'0px','borderTopWidth':'0px','borderLeftWidth':'0px','borderRightWidth':'0px','borderBottomWidth':'0px','borderTopLeftRadius':'1px','borderTopRightRadius':'1px','borderBottomLeftRadius':'1px','borderBottomRightRadius':'1px'}"
      slot="r0-c2" area="r0-c2"/>
    <NucGridCell v-bind:wrap="true" v-bind:reverse="false" overflow="hidden" direction="column"
      v-bind:showInDevice="['xs','sm','md','lg']" verticalAlignment="top" horizontalAlignment="left"
      id="b22623d0-b1a9-4d78-a06d-f63c511c558f" v-bind:col="0" v-bind:row="0" v-bind:colSpan="1" v-bind:rowSpan="1"
      v-bind:marginTop="0" v-bind:marginLeft="0" v-bind:marginRight="0" v-bind:marginBottom="0"
      v-bind:style="{'background':'transparent','paddingTop':'0px','borderColor':'','borderStyle':'solid','borderWidth':'0px','paddingLeft':'0px','borderRadius':'0px','paddingRight':'0px','paddingBottom':'0px','borderTopWidth':'0px','borderLeftWidth':'0px','borderRightWidth':'0px','borderBottomWidth':'0px','borderTopLeftRadius':'1px','borderTopRightRadius':'1px','borderBottomLeftRadius':'1px','borderBottomRightRadius':'1px'}"
      slot="r0-c3" area="r0-c3"/>
    <NucGridCell v-bind:wrap="true" v-bind:reverse="false" overflow="hidden" direction="column"
      v-bind:showInDevice="['xs','sm','md','lg']" verticalAlignment="top" horizontalAlignment="left"
      id="3d050749-b813-4c8c-be19-2979e34e5a32" v-bind:col="0" v-bind:row="0" v-bind:colSpan="1" v-bind:rowSpan="1"
      v-bind:marginTop="0" v-bind:marginLeft="0" v-bind:marginRight="0" v-bind:marginBottom="0"
      v-bind:style="{'background':'transparent','paddingTop':'0px','borderColor':'','borderStyle':'solid','borderWidth':'0px','paddingLeft':'0px','borderRadius':'0px','paddingRight':'0px','paddingBottom':'0px','borderTopWidth':'0px','borderLeftWidth':'0px','borderRightWidth':'0px','borderBottomWidth':'0px','borderTopLeftRadius':'1px','borderTopRightRadius':'1px','borderBottomLeftRadius':'1px','borderBottomRightRadius':'1px'}"
      slot="r1-c0" area="r1-c0"/>
    <NucGridCell v-bind:wrap="true" v-bind:reverse="false" overflow="hidden" direction="column"
      v-bind:showInDevice="['xs','sm','md','lg']" verticalAlignment="top" horizontalAlignment="left"
      id="251ff6dc-5a94-4074-892f-fc0350c055a4" v-bind:col="0" v-bind:row="0" v-bind:colSpan="1" v-bind:rowSpan="1"
      v-bind:marginTop="0" v-bind:marginLeft="0" v-bind:marginRight="0" v-bind:marginBottom="0"
      v-bind:style="{'background':'transparent','paddingTop':'0px','borderColor':'','borderStyle':'solid','borderWidth':'0px','paddingLeft':'0px','borderRadius':'0px','paddingRight':'0px','paddingBottom':'0px','borderTopWidth':'0px','borderLeftWidth':'0px','borderRightWidth':'0px','borderBottomWidth':'0px','borderTopLeftRadius':'1px','borderTopRightRadius':'1px','borderBottomLeftRadius':'1px','borderBottomRightRadius':'1px'}"
      slot="r1-c1" area="r1-c1"/>
    <NucGridCell v-bind:wrap="true" v-bind:reverse="false" overflow="hidden" direction="column"
      v-bind:showInDevice="['xs','sm','md','lg']" verticalAlignment="top" horizontalAlignment="left"
      id="d8d5253a-e94a-44b7-a50f-b4098ce86d4b" v-bind:col="0" v-bind:row="0" v-bind:colSpan="1" v-bind:rowSpan="1"
      v-bind:marginTop="0" v-bind:marginLeft="0" v-bind:marginRight="0" v-bind:marginBottom="0"
      v-bind:style="{'background':'transparent','paddingTop':'0px','borderColor':'','borderStyle':'solid','borderWidth':'0px','paddingLeft':'0px','borderRadius':'0px','paddingRight':'0px','paddingBottom':'0px','borderTopWidth':'0px','borderLeftWidth':'0px','borderRightWidth':'0px','borderBottomWidth':'0px','borderTopLeftRadius':'1px','borderTopRightRadius':'1px','borderBottomLeftRadius':'1px','borderBottomRightRadius':'1px'}"
      slot="r1-c2" area="r1-c2"/>
    <NucGridCell v-bind:wrap="true" v-bind:reverse="false" overflow="hidden" direction="column"
      v-bind:showInDevice="['xs','sm','md','lg']" verticalAlignment="top" horizontalAlignment="left"
      id="19f0d442-983a-43f4-a3ac-11fae58fc017" v-bind:col="0" v-bind:row="0" v-bind:colSpan="1" v-bind:rowSpan="1"
      v-bind:marginTop="0" v-bind:marginLeft="0" v-bind:marginRight="0" v-bind:marginBottom="0"
      v-bind:style="{'background':'transparent','paddingTop':'0px','borderColor':'','borderStyle':'solid','borderWidth':'0px','paddingLeft':'0px','borderRadius':'0px','paddingRight':'0px','paddingBottom':'0px','borderTopWidth':'0px','borderLeftWidth':'0px','borderRightWidth':'0px','borderBottomWidth':'0px','borderTopLeftRadius':'1px','borderTopRightRadius':'1px','borderBottomLeftRadius':'1px','borderBottomRightRadius':'1px'}"
      slot="r1-c3" area="r1-c3"/>
    <NucGridCell v-bind:wrap="true" v-bind:reverse="false" overflow="hidden" direction="column"
      v-bind:showInDevice="['xs','sm','md','lg']" verticalAlignment="top" horizontalAlignment="left"
      id="a1c98726-f636-4cda-935b-0ea3be97ec1f" v-bind:col="0" v-bind:row="0" v-bind:colSpan="1" v-bind:rowSpan="1"
      v-bind:marginTop="0" v-bind:marginLeft="0" v-bind:marginRight="0" v-bind:marginBottom="0"
      v-bind:style="{'background':'transparent','paddingTop':'0px','borderColor':'','borderStyle':'solid','borderWidth':'0px','paddingLeft':'0px','borderRadius':'0px','paddingRight':'0px','paddingBottom':'0px','borderTopWidth':'0px','borderLeftWidth':'0px','borderRightWidth':'0px','borderBottomWidth':'0px','borderTopLeftRadius':'1px','borderTopRightRadius':'1px','borderBottomLeftRadius':'1px','borderBottomRightRadius':'1px'}"
      slot="r2-c0" area="r2-c0"/>
    <NucGridCell v-bind:wrap="true" v-bind:reverse="false" overflow="hidden" direction="column"
      v-bind:showInDevice="['xs','sm','md','lg']" verticalAlignment="top" horizontalAlignment="left"
      id="3de6fdc3-3151-41fe-be3a-e9234fe7a455" v-bind:col="0" v-bind:row="0" v-bind:colSpan="1" v-bind:rowSpan="1"
      v-bind:marginTop="0" v-bind:marginLeft="0" v-bind:marginRight="0" v-bind:marginBottom="0"
      v-bind:style="{'background':'transparent','paddingTop':'0px','borderColor':'','borderStyle':'solid','borderWidth':'0px','paddingLeft':'0px','borderRadius':'0px','paddingRight':'0px','paddingBottom':'0px','borderTopWidth':'0px','borderLeftWidth':'0px','borderRightWidth':'0px','borderBottomWidth':'0px','borderTopLeftRadius':'1px','borderTopRightRadius':'1px','borderBottomLeftRadius':'1px','borderBottomRightRadius':'1px'}"
      slot="r2-c1" area="r2-c1">
      <WTags top="49.70059880239521%" left="0%" size="md" v-bind:limit="255" v-bind:snapX="false" v-bind:snapY="false"
        v-bind:value="[]" v-bind:disabled="false" position="absolute" v-bind:required="false" v-bind:tagPills="false"
        inputType="text" separator="" tagVariant="secondary" v-bind:addOnChange="false" v-bind:noTagRemove="false"
        placeholder="Add tag..." v-bind:noAddOnEnter="false" addButtonText="Add" invalidTagText="Invalid tag(s)"
        v-bind:removeOnDelete="false" tagRemoveLabel="Remove tag" tagRemovedLabel="Tag removed"
        addButtonVariant="outline-secondary" duplicateTagText="Duplicate tag(s)"
        id="823a4e5d-a90a-4af9-9bc7-337c63804805"
        v-bind:style="{'width':'auto','height':'auto','fontSize':'18px','maxWidth':'','minWidth':'','tabIndex':'0px','boxShadow':'','fontStyle':'normal','marginTop':'0px','maxHeight':'','minHeight':'','textAlign':'','fontFamily':'Roboto-Regular,Roboto','fontWeight':'','lineHeight':'','marginLeft':'0px','paddingTop':'0px','textShadow':'','visibility':'visible','marginRight':'0px','paddingLeft':'0px','marginBottom':'0px','paddingRight':'0px','paddingBottom':'0px','textDecoration':'none','horizontalHeight':'37.5347px'}"/>
    </NucGridCell>
    <NucGridCell v-bind:wrap="true" v-bind:reverse="false" overflow="hidden" direction="column"
      v-bind:showInDevice="['xs','sm','md','lg']" verticalAlignment="top" horizontalAlignment="left"
      id="db319e92-349a-433c-9930-8a8d12a8b008" v-bind:col="0" v-bind:row="0" v-bind:colSpan="1" v-bind:rowSpan="1"
      v-bind:marginTop="0" v-bind:marginLeft="0" v-bind:marginRight="0" v-bind:marginBottom="0"
      v-bind:style="{'background':'transparent','paddingTop':'0px','borderColor':'','borderStyle':'solid','borderWidth':'0px','paddingLeft':'0px','borderRadius':'0px','paddingRight':'0px','paddingBottom':'0px','borderTopWidth':'0px','borderLeftWidth':'0px','borderRightWidth':'0px','borderBottomWidth':'0px','borderTopLeftRadius':'1px','borderTopRightRadius':'1px','borderBottomLeftRadius':'1px','borderBottomRightRadius':'1px'}"
      slot="r2-c2" area="r2-c2"/>
    <NucGridCell v-bind:wrap="true" v-bind:reverse="false" overflow="hidden" direction="column"
      v-bind:showInDevice="['xs','sm','md','lg']" verticalAlignment="top" horizontalAlignment="left"
      id="6355adc2-f9b5-4a9a-b5ab-2cc73b0ba20f" v-bind:col="0" v-bind:row="0" v-bind:colSpan="1" v-bind:rowSpan="1"
      v-bind:marginTop="0" v-bind:marginLeft="0" v-bind:marginRight="0" v-bind:marginBottom="0"
      v-bind:style="{'background':'transparent','paddingTop':'0px','borderColor':'','borderStyle':'solid','borderWidth':'0px','paddingLeft':'0px','borderRadius':'0px','paddingRight':'0px','paddingBottom':'0px','borderTopWidth':'0px','borderLeftWidth':'0px','borderRightWidth':'0px','borderBottomWidth':'0px','borderTopLeftRadius':'1px','borderTopRightRadius':'1px','borderBottomLeftRadius':'1px','borderBottomRightRadius':'1px'}"
      slot="r2-c3" area="r2-c3"/>
    <NucGridCell v-bind:wrap="true" v-bind:reverse="false" overflow="hidden" direction="column"
      v-bind:showInDevice="['xs','sm','md','lg']" verticalAlignment="top" horizontalAlignment="left"
      id="c7775f66-26fa-4615-8214-8baa70a38613" v-bind:col="0" v-bind:row="0" v-bind:colSpan="1" v-bind:rowSpan="1"
      v-bind:marginTop="0" v-bind:marginLeft="0" v-bind:marginRight="0" v-bind:marginBottom="0"
      v-bind:style="{'background':'transparent','paddingTop':'0px','borderColor':'','borderStyle':'solid','borderWidth':'0px','paddingLeft':'0px','borderRadius':'0px','paddingRight':'0px','paddingBottom':'0px','borderTopWidth':'0px','borderLeftWidth':'0px','borderRightWidth':'0px','borderBottomWidth':'0px','borderTopLeftRadius':'1px','borderTopRightRadius':'1px','borderBottomLeftRadius':'1px','borderBottomRightRadius':'1px'}"
      slot="r3-c0" area="r3-c0">
      <WReadonlyRating id="366505a1-e554-44d9-93ca-cba2a1782ef5" top="37.81305597372383%" form=""
        left="3.3473090934084815%" size="md" v-bind:snapX="false" v-bind:snapY="false" stars="5" v-bind:inline="false"
        locale="" options="" variant="default" v-bind:disabled="false" iconFull="star-fill" iconHalf="star-half"
        v-bind:noBorder="false" position="absolute" v-bind:readonly="true" iconClear="x" iconEmpty="star" precision=""
        v-bind:showClear="false" v-bind:showValue="false" localValue="3" ratingColor="#495057"
        v-bind:showValueMax="false" ncTooltipText="" v-bind:hasClearButton="false" nucalScaleWidth=""
        nucalScaleHeight="" ncFocusBorderColor="#000000" ncHoverBorderColor="#000000" ncDisableBorderColor="#000000"
        ncFocusBackgroundColor="transparent" ncHoverBackgroundColor="transparent" ncDisableBackgroundColor="transparent"
        v-bind:style="{'width':'','height':'','maxWidth':'','minWidth':'300px','tabIndex':'0px','boxShadow':'','marginTop':'','maxHeight':'','minHeight':'','lineHeight':'1.4','marginLeft':'','paddingTop':'','visibility':'visible','borderStyle':'solid','marginRight':'','paddingLeft':'','marginBottom':'','paddingRight':'','paddingBottom':'','borderTopWidth':'1px','textDecoration':'none','borderLeftWidth':'1px','borderRightWidth':'1px','horizontalHeight':'37.5347px','borderBottomWidth':'1px','borderTopLeftRadius':'4px','borderTopRightRadius':'4px','borderBottomLeftRadius':'4px','borderBottomRightRadius':'4px'}"/>
    </NucGridCell>
    <NucGridCell v-bind:wrap="true" v-bind:reverse="false" overflow="hidden" direction="column"
      v-bind:showInDevice="['xs','sm','md','lg']" verticalAlignment="top" horizontalAlignment="left"
      id="425f3c67-d627-42f7-9d86-749e04124f82" v-bind:col="0" v-bind:row="0" v-bind:colSpan="1" v-bind:rowSpan="1"
      v-bind:marginTop="0" v-bind:marginLeft="0" v-bind:marginRight="0" v-bind:marginBottom="0"
      v-bind:style="{'background':'transparent','paddingTop':'0px','borderColor':'','borderStyle':'solid','borderWidth':'0px','paddingLeft':'0px','borderRadius':'0px','paddingRight':'0px','paddingBottom':'0px','borderTopWidth':'0px','borderLeftWidth':'0px','borderRightWidth':'0px','borderBottomWidth':'0px','borderTopLeftRadius':'1px','borderTopRightRadius':'1px','borderBottomLeftRadius':'1px','borderBottomRightRadius':'1px'}"
      slot="r3-c1" area="r3-c1">
      <WRadio top="20.46783625730994%" left="4.108584005869406%" name="" size="md" label="Option A" v-bind:plain="false"
        v-bind:snapX="false" v-bind:snapY="false" theme="theme--light01" v-bind:button="false" v-bind:inline="false"
        fontSize="14px" position="absolute" v-bind:selected="false" v-bind:autofocus="false" v-bind:isEnabled="true"
        textAlign="left" fontFamily="Roboto-Regular,Roboto" fontWeight="normal" ncTypography="custom"
        v-bind:indeterminate="false" labelPosition="right" ncTooltipText="" nucalScaleWidth="" ncFocusFontColor="black"
        ncHoverFontColor="black" nucalScaleHeight="" ncDisableFontColor="black" ncFocusBorderColor="black"
        ncHoverBorderColor="black" ncDisableBorderColor="black" ncFocusBackgroundColor="transparent"
        ncHoverBackgroundColor="transparent" ncDisableBackgroundColor="transparent"
        id="21f8a3f8-6885-4feb-8a71-17b586a42c40"
        v-bind:style="{'color':'','maxWidth':'','minWidth':'','tabIndex':'0px','boxShadow':'','fontStyle':'none','marginTop':'0px','maxHeight':'','minHeight':'','lineHeight':'','marginLeft':'3px','paddingTop':'0px','textShadow':'','visibility':'visible','marginRight':'0px','paddingLeft':'0px','marginBottom':'0px','paddingRight':'0px','paddingBottom':'0px','textDecoration':'none'}"/>
      <WDaysSpin v-bind:max="6" v-bind:min="0" top="45.02923976608187%" left="2.925531914893617%" size="md"
        v-bind:step="1" v-bind:wrap="false" v-bind:snapX="false" v-bind:snapY="false" v-bind:value="0"
        v-bind:inline="false" v-bind:disabled="false" position="absolute" v-bind:readonly="false"
        v-bind:vertical="false" formatter="day" placeholder="Write a text to display in placeholder"
        ncTypography="body1" id="848f7adf-35e2-4191-9201-63c56b2d2908"
        v-bind:style="{'color':'#212529','maxWidth':'','minWidth':'','fontStyle':'body1','marginTop':'0px','maxHeight':'','minHeight':'','textAlign':'center','fontFamily':'Roboto-Regular,Roboto','fontWeight':'normal','lineHeight':'','marginLeft':'0px','paddingTop':'0px','marginRight':'0px','paddingLeft':'0px','marginBottom':'0px','paddingRight':'0px','paddingBottom':'0px','textDecoration':'none'}"/>
    </NucGridCell>
    <NucGridCell v-bind:wrap="true" v-bind:reverse="false" overflow="hidden" direction="column"
      v-bind:showInDevice="['xs','sm','md','lg']" verticalAlignment="top" horizontalAlignment="left"
      id="79736e42-5dc8-4b9d-8627-cd1ea48c3509" v-bind:col="0" v-bind:row="0" v-bind:colSpan="1" v-bind:rowSpan="1"
      v-bind:marginTop="0" v-bind:marginLeft="0" v-bind:marginRight="0" v-bind:marginBottom="0"
      v-bind:style="{'background':'transparent','paddingTop':'0px','borderColor':'','borderStyle':'solid','borderWidth':'0px','paddingLeft':'0px','borderRadius':'0px','paddingRight':'0px','paddingBottom':'0px','borderTopWidth':'0px','borderLeftWidth':'0px','borderRightWidth':'0px','borderBottomWidth':'0px','borderTopLeftRadius':'1px','borderTopRightRadius':'1px','borderBottomLeftRadius':'1px','borderBottomRightRadius':'1px'}"
      slot="r3-c2" area="r3-c2">
      <WLargeRating id="a914f9c5-8b93-4ad6-8a9d-a5f89c66ec13" top="36.93718352264951%" form="" left="9.91099350493144%"
        size="lg" v-bind:snapX="false" v-bind:snapY="false" stars="5" v-bind:inline="false" locale="" options=""
        variant="default" v-bind:disabled="false" iconFull="star-fill" iconHalf="star-half" v-bind:noBorder="false"
        position="absolute" v-bind:readonly="false" iconClear="x" iconEmpty="star" precision="" v-bind:showClear="false"
        v-bind:showValue="false" localValue="3" ratingColor="#495057" v-bind:showValueMax="false" ncTooltipText=""
        v-bind:hasClearButton="false" nucalScaleWidth="" nucalScaleHeight="" ncFocusBorderColor="#000000"
        ncHoverBorderColor="#000000" ncDisableBorderColor="#000000" ncFocusBackgroundColor="transparent"
        ncHoverBackgroundColor="transparent" ncDisableBackgroundColor="transparent"
        v-bind:style="{'width':'','height':'','maxWidth':'','minWidth':'300px','tabIndex':'0px','boxShadow':'','marginTop':'','maxHeight':'','minHeight':'','lineHeight':'1.4','marginLeft':'','paddingTop':'','visibility':'visible','borderStyle':'solid','marginRight':'','paddingLeft':'','marginBottom':'','paddingRight':'','paddingBottom':'','borderTopWidth':'1px','textDecoration':'none','borderLeftWidth':'1px','borderRightWidth':'1px','horizontalHeight':'37.5347px','borderBottomWidth':'1px','borderTopLeftRadius':'4px','borderTopRightRadius':'4px','borderBottomLeftRadius':'4px','borderBottomRightRadius':'4px'}"/>
    </NucGridCell>
    <NucGridCell v-bind:wrap="true" v-bind:reverse="false" overflow="hidden" direction="column"
      v-bind:showInDevice="['xs','sm','md','lg']" verticalAlignment="top" horizontalAlignment="left"
      id="e5974102-90b1-404d-9615-7c98d2c595cf" v-bind:col="0" v-bind:row="0" v-bind:colSpan="1" v-bind:rowSpan="1"
      v-bind:marginTop="0" v-bind:marginLeft="0" v-bind:marginRight="0" v-bind:marginBottom="0"
      v-bind:style="{'background':'transparent','paddingTop':'0px','borderColor':'','borderStyle':'solid','borderWidth':'0px','paddingLeft':'0px','borderRadius':'0px','paddingRight':'0px','paddingBottom':'0px','borderTopWidth':'0px','borderLeftWidth':'0px','borderRightWidth':'0px','borderBottomWidth':'0px','borderTopLeftRadius':'1px','borderTopRightRadius':'1px','borderBottomLeftRadius':'1px','borderBottomRightRadius':'1px'}"
      slot="r3-c3" area="r3-c3"/>
  </NucGridPage>
</template>
<script>
export default {
  name: 'Screen2',
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