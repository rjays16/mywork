<template>

<section>
  <div id="founders">

    <b-button style="width: 1295px; background-color: white; color: darkblue; font-size: 40px"  v-b-toggle.collapse-a @click="visible = !visible"><span style="float: left">THE FOUNDERS OF THE ASD</span>
      <img v-if="visible===false" style="width: 60px; float: right" src="../../image/left.svg">
      <img v-else style="width: 60px; float: right" src="../../image/down.png">
    </b-button>

    <!--      &lt;!&ndash; Via array of string IDs passed to directive value &ndash;&gt;-->
    <!--      <b-button v-b-toggle="['collapse-a', 'collapse-b']">Toggle Collapse A and B</b-button>-->

    <!-- Elements to collapse -->
    <b-collapse id="collapse-a" class="mt-2">
      <b-card>
        <table width="775" border="0">
          <tr>
            <td width="408">AUNG, Phyu P. (Houston)</td>
            <td width="240">PALIZA, Arnelfa C. (Manila)</td>
          </tr>
          <tr>
            <td>CHOW, Steven (Kuala Lumpur) </td>
            <td>PHUNG, Thuy L. (Houston)</td>
          </tr>
          <tr>
            <td>ISMAEL, Daisy (Manila) </td>
            <td>RAMAM, M (New Delhi)</td>
          </tr>
          <tr>
            <td>JAMORA, Maria Jasmin J. (Manila)</td>
            <td>SUN, Jianfang (Nanjing) </td>
          </tr>
          <tr>
            <td>KIMURA, Tetsunori (Sapporo)</td>
            <td>TAN, Suat Hoon (Singapore) </td>
          </tr>
          <tr>
            <td>LEE, Bang Rom (Kuala Lumpur)</td>
            <td>TEE, Shang-Ian (Singapore)</td>
          </tr>
          <tr>
            <td>LEE, Dong-Youn (Seoul)</td>
            <td>VERALLO-ROWELL, Vermen M. (Manila)</td>
          </tr>
          <tr>
            <td>LEE, Joyce Siong See (Singapore)</td>
            <td>WU, Yu-Hung (Taipei)</td>
          </tr>
          <tr>
            <td>NOPPAKUM, Nopadon (Bangkok)</td>
            <td>WANG, Lei (Xian</td>
          </tr>
          <tr>
            <td>OHATA, Chika (Fukuoka)</td>
            <td>YAMAMOTO, Osamu (Tottori)</td>
          </tr>
        </table>
      </b-card>
    </b-collapse>
  </div>

  <div id="dsp">
    <b-button style="width: 595px; background-color: white; color: darkblue; font-size: 40px"  v-b-toggle.collapse-b @click="visible2 = !visible2"><span style="float: left">DSP Board of Directors</span>
      <img v-if="visible2===false" style="width: 60px; float: right" src="../../image/left.svg">
      <img v-else style="width: 60px; float: right" src="../../image/down.png">
    </b-button>
    <b-collapse id="collapse-b" class="mt-2">
      <b-card>
        <table width="313" border="0">
          <tr>
            <td width="303">Arnelfa C. Paliza, MD, FPDS</td>
          </tr>
          <tr>
            <td>President </td>
          </tr>
          <tr>
            <td>Georgina C Pastorfide MD, FPDS </td>
          </tr>
          <tr>
            <td>Vice-President</td>
          </tr>
        </table></b-card>
    </b-collapse>
  </div>

  <div id="organizing">
    <b-button style="width: 595px; background-color: white; color: darkblue; font-size: 40px"  v-b-toggle.collapse-c @click="visible3 = !visible3"><span style="float: left">Organizing Committee</span>
      <img v-if="visible3===false" style="width: 60px; float: right" src="../../image/left.svg">
      <img v-else style="width: 60px; float: right" src="../../image/down.png">
    </b-button>
    <b-collapse id="collapse-c" class="mt-2">
      <b-card>
        <table width="313" border="0">
          <tr>
            <td width="303">Arnelfa C. Paliza, MD, FPDS</td>
          </tr>
          <tr>
            <td>Overall Chair</td>
          </tr>
        </table></b-card>
    </b-collapse>
  </div>

  <div id="scientific">
    <b-button style="width: 595px; background-color: white; color: darkblue; font-size: 40px"  v-b-toggle.collapse-d @click="visible4 = !visible4"><span style="float: left">SCIENTIFIC</span>
      <img v-if="visible4===false" style="width: 60px; float: right" src="../../image/left.svg">
      <img v-else style="width: 60px; float: right" src="../../image/down.png">
    </b-button>
    <b-collapse id="collapse-d" class="mt-2">
      <b-card>
        <table width="319" border="0">
          <tr>
            <td width="227">Flordeliza Casintahan, MD, FPDS</td>
          </tr>
          <tr>
            <td>Maria Jasmin J. Jamora, MD, FPDS</td>
          </tr>
          <tr>
            <td>Co-Chairs</td>
          </tr>
          <tr>
            <td>&nbsp;</td>
          </tr>
          <tr>
            <td>Bryan Guevara, MD, FPDS</td>
          </tr>
        </table></b-card>
    </b-collapse>
  </div>

  <div id="ways">
    <b-button style="width: 595px; background-color: white; color: darkblue; font-size: 40px"  v-b-toggle.collapse-e @click="visible5 = !visible5"><span style="float: left">WAYS & MEANS</span>
      <img v-if="visible5===false" style="width: 60px; float: right" src="../../image/left.svg">
      <img v-else style="width: 60px; float: right" src="../../image/down.png">
    </b-button>
    <b-collapse id="collapse-e" class="mt-2">
      <b-card>
        <table width="349" border="0">
          <tr>
            <td width="317">Georgina C. Pastorfide, MD, FPDS</td>
          </tr>
          <tr>
            <td>Chair</td>
          </tr>
          <tr>
            <td>&nbsp;</td>
          </tr>
          <tr>
            <td>Maria Franchesca S. Quinio, MD, FPDS</td>
          </tr>
        </table></b-card>
    </b-collapse>
  </div>

  <div id="physical">
    <b-button style="width: 595px; background-color: white; color: darkblue; font-size: 40px"  v-b-toggle.collapse-f @click="visible6 = !visible6"><span style="float: left">PHYSICAL ARRANGEMENTS</span>
      <img v-if="visible6===false" style="width: 60px; float: right" src="../../image/left.svg">
      <img v-else style="width: 60px; float: right" src="../../image/down.png">
    </b-button>
    <b-collapse id="collapse-f" class="mt-2">
      <b-card>
        <table width="432" border="0">
          <tr>
            <td width="244">Andrea Marie B. Bernales- Mendoza, MD, FPDS</td>
          </tr>
          <tr>
            <td>Chair</td>
          </tr>
          <tr>
            <td>&nbsp;</td>
          </tr>
          <tr>
            <td>Johaness F. Dayrit. MD, FPDS</td>
          </tr>
        </table></b-card>
    </b-collapse>
  </div>

  <div id="publicity">
    <b-button style="width: 595px; background-color: white; color: darkblue; font-size: 40px"  v-b-toggle.collapse-g @click="visible7 = !visible7"><span style="float: left">PUBLICITY</span>
      <img v-if="visible7===false" style="width: 60px; float: right" src="../../image/left.svg">
      <img v-else style="width: 60px; float: right" src="../../image/down.png">
    </b-button>
    <b-collapse id="collapse-g" class="mt-2">
      <b-card>
        <table width="346" border="0">
          <tr>
            <td width="340">Kara Melissa Torres-Culala, MD, FPDS</td>
          </tr>
          <tr>
            <td>Chair</td>
          </tr>
          <tr>
            <td>&nbsp;</td>
          </tr>
          <tr>
            <td>Terese Monette Aquino-Agas, MD, FPDS </td>
          </tr>
        </table></b-card>
    </b-collapse>
  </div>

  <div id="registration">
    <b-button style="width: 595px; background-color: white; color: darkblue; font-size: 40px"  v-b-toggle.collapse-i @click="visible9 = !visible9"><span style="float: left">REGISTRATION</span>
      <img v-if="visible9===false" style="width: 60px; float: right" src="../../image/left.svg">
      <img v-else style="width: 60px; float: right" src="../../image/down.png">
    </b-button>
    <b-collapse id="collapse-i" class="mt-2">
      <b-card>
        <table width="346" border="0">
          <tr>
            <td width="340">Mary Elizabeth Danga, MD, FPDS</td>
          </tr>
          <tr>
            <td>Chair</td>
          </tr>
          <tr>
            <td>&nbsp;</td>
          </tr>
          <tr>
            <td>Tanya Perez-Chua, MD, FPDS</td>
          </tr>
        </table></b-card>
    </b-collapse>
  </div>

  <div id="research">
    <b-button style="width: 595px; background-color: white; color: darkblue; font-size: 40px"  v-b-toggle.collapse-j @click="visible10 = !visible10"><span style="float: left">RESEARCH</span>
      <img v-if="visible10===false" style="width: 60px; float: right" src="../../image/left.svg">
      <img v-else style="width: 60px; float: right" src="../../image/down.png">
    </b-button>
    <b-collapse id="collapse-j" class="mt-2">
      <b-card>
        <table width="408" border="0">
          <tr>
            <td width="398">Mara Therese P. Evangelista-Huber, MD, FPDS</td>
          </tr>
          <tr>
            <td>Chair</td>
          </tr>
          <tr>
            <td>&nbsp;</td>
          </tr>
          <tr>
            <td>Eileen Liesl A. Cubillan, MD, FPDS</td>
          </tr>
          <tr>
            <td>Riza R. Milante, MD, FPDS</td>
          </tr>
        </table></b-card>
    </b-collapse>
  </div>
</section>
</template>

<script>
export default {
  name: "Founders_content",
  data(){
    return {
      visible: false,
      visible2: false,
      visible3: false,
      visible4: false,
      visible5: false,
      visible6: false,
      visible7: false,
      visible8: false,
      visible9: false,
      visible10: false,
    }
  }
}
</script>

<style scoped>

</style>