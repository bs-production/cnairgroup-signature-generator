<template>
  <div>
      <section>
        <table cellpadding="0" cellspacing="0" border="0" style=
        "background: none; border-width: 0px; border: 0px; margin: 0; padding: 0;">
        <tr>
            <td valign="top" style=
            "padding-top: 0; padding-bottom: 0; padding-left: 0; padding-right: 7px; border-top: 0; border-bottom: 0: border-left: 0;">
            <a href="https://www.cnairgroup.com">
   
            <img v-show="assSwitch" width="220" height="139" style="width: 220px; max-width: 220px !important; height: 139px; max-height: 139px !important; margin-top: 5px;" id="preview-image-url" src="https://cdn.treehouseinternetgroup.com/cms_images/3643/cnairgroup-signature_logo-bar.jpg" name="preview-image-url" />
     
      
            <img v-show="!assSwitch" width="190" height="121" style="width: 190px; max-width: 190px !important; height: 121px; max-height: 121px !important; margin-top: 5px;" id="preview-image-url" src="https://cdn.treehouseinternetgroup.com/cms_images/3643/cnairgroup-signature_logo-bar.jpg" name="preview-image-url" />
   

              </a>
            </td>
            
            <td style=
            "padding-top: 0; padding-bottom: 0; padding-left: 5px; padding-right: 0;">
            <table cellpadding="0" cellspacing="0" border="0" style=
            "background: none; border-width: 0px; border: 0px; margin: 0; padding: 0;">
              <tr>
                  <td colspan="2" style=
                  "padding-bottom: 5px; color: #0e3b7b; font-size: 18px; font-family: Arial, Helvetica, sans-serif;">
                  {{fullName}}
                  </td>
                </tr>
                <tr>
                  <td colspan="2" style=
                  "color: #333333; font-size: 14px; font-family: Arial, Helvetica, sans-serif;">
                  <em>{{title}}</em>
                  </td>
                </tr>
              <div v-show="!assSwitch">

              </div>
    
                <tr v-show="assSwitch">
                  <td colspan="2" style=
                  "color: #333333; font-size: 14px; font-family: Arial, Helvetica, sans-serif;">
                  {{association}}
                  </td>
                </tr>
             
                <tr>
                  <td width="20" valign="top" style=
                  "vertical-align: top; width: 20px; color: #0e3b7b; font-size: 14px; font-family: Arial, Helvetica, sans-serif;">
                  p:
                  </td>
                  <td valign="top" style=
                  "vertical-align: top; color: #333333; font-size: 14px; font-family: Arial, Helvetica, sans-serif;">
                  {{phone}}
                  </td>
                </tr>
                               <tr>
                  <td width="20" valign="top" style=
                  "vertical-align: top; width: 20px; color: #0e3b7b; font-size: 14px; font-family: Arial, Helvetica, sans-serif;">
                  w:
                  </td>
                  <td valign="top" style=
                  "vertical-align: top; color: #333333; font-size: 14px; font-family: Arial, Helvetica, sans-serif;">
                  <a href="https://www.cnairgroup.com" target="_blank" style=
                  "color: #333333; text-decoration: none; font-weight: normal; font-size: 14px;">
                    cnairgroup.com</a>
                    &nbsp;&nbsp;
                  </td>
                </tr>
                <tr>
                    <td width="20" valign="top" style=
                    "vertical-align: top; width: 20px; color: #0e3b7b; font-size: 14px; font-family: Arial, Helvetica, sans-serif;">
                    e:
                    </td>
                    <td valign="top" style=
                    "vertical-align: top; color: #333333; font-size: 14px; font-family: Arial, Helvetica, sans-serif;">
                    <a :href="`mailto:${this.email}`" style="color: #333333; text-decoration: none; font-weight: normal; font-size: 14px;">{{email}}</a>
                      &nbsp;&nbsp;
                    </td>
                  </tr>
                 <tr>
                  <td colspan="2" style="padding-top: 5px;">
                    <a href="https://www.facebook.com/profile.php?id=61555387024191" target="_blank" style=
                    "border-width:0px; border:0px; text-decoration: none;"><img width="25"
                    height="25" style=
                    "border: none; width: 25px; max-width: 25px !important; height: 25px; max-height: 25px !important;"
                    src=
                    "https://dc69b531ebf7a086ce97-290115cc0d6de62a29c33db202ae565c.ssl.cf1.rackcdn.com/1874/facebook.png" /></a>
                    
                    <a href="https://www.linkedin.com/company/contractor-nation-air-group" target="_blank" style=
                    "border-width:0px; border:0px; text-decoration: none;"><img width="25"
                    height="25" style=
                    "border: none; width: 25px; max-width: 25px !important; height: 25px; max-height: 25px !important;"
                    src=
                    "https://dc69b531ebf7a086ce97-290115cc0d6de62a29c33db202ae565c.ssl.cf1.rackcdn.com/1874/linkedin.png" /></a>
                    
                    <!-- <a href="https://www.youtube.com/channel/UCeZriiWQwELIGcWiZV3vGeg" target="_blank"
                    style=
                    "border-width:0px; border:0px; text-decoration: none;"><img width="25"
                    height="25" style=
                    "border: none; width: 25px; max-width: 25px !important; height: 25px; max-height: 25px !important;"
                    src=
                    "https://dc69b531ebf7a086ce97-290115cc0d6de62a29c33db202ae565c.ssl.cf1.rackcdn.com/2721/youtube.png" /></a>

                    <a href="https://twitter.com/brownroofingct" target="_blank"
                    style=
                    "border-width:0px; border:0px; text-decoration: none;"><img width="25"
                    height="25" style=
                    "border: none; width: 25px; max-width: 25px !important; height: 25px; max-height: 25px !important;"
                    src=
                    "https://dc69b531ebf7a086ce97-290115cc0d6de62a29c33db202ae565c.ssl.cf1.rackcdn.com/1253/twitter-circle-icon-2.png" /></a>

                    <a href="https://www.instagram.com/brownroofingct/" target="_blank"
                    style=
                    "border-width:0px; border:0px; text-decoration: none;"><img width="25"
                    height="25" style=
                    "border: none; width: 25px; max-width: 25px !important; height: 25px; max-height: 25px !important;"
                    src=
                    "https://dc69b531ebf7a086ce97-290115cc0d6de62a29c33db202ae565c.ssl.cf1.rackcdn.com/1874/instagram.png" /></a> -->
                  </td>
                </tr> 
              </table>
            </td>
          </tr>
        </table>
    </section>
  </div>
</template>
<script>
export default {
  name: 'outputSignature',
  props: {
    fullName: {
      type: String,
      required: true
    },
    title: {
      type: String,
      required: true
    },
    association: {
      type: String,
      required: true
    },
    phone: {
      type: String,
      required: true
    },
    email: {
      type: String,
      required: true
    },
    assSwitch: {
      type: Boolean,
      required: true
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1, h2 {
  font-weight: normal;
}

ul {
  list-style-type: none;
  padding: 0;
}

li {
  display: inline-block;
  margin: 0 10px;
}

a {
  color: #0e3b7b;
}
</style>
