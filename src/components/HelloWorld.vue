<template>
  <div>

  <div id="box"></div>
    <div id="img1">
      <img src="../../image/ONE_trans.png">
    </div>

    <div id="img2">
      <img src="../../image/Appreciation.png">
    </div>

    <div id="cover">
      <img src="../../image/pexels.jpeg">
    </div>

      <div id="contain_text">
    <div id="text">
      <center>
        <h1 class="for_overline">4th ANNUAL MEETING OF </h1>
        <h1>ASIAN SOCIETY OF DERMAPATHOLOGY </h1>
        <h1 class="for_overline">OCTOBER 24 -25 2022</h1>
      </center>
    </div>
  </div>

    <div id="bottom-top"></div>
      <div id="text2">
        <center><h1>SAVE THE DATE!</h1></center>
        <center><p>REGISTRATION OPENS ON APRIL 18, 2022</p></center>
      </div>

    <div id="text-message">
      <div id="content">
         <h1>Message from the ASD President</h1>
      </div>
          </div>
    <div id="profile">
      <img src="../../image/Yuhung_Profile.png">
    </div>
    <div id="box_inside"></div>
    <div id="box_outside">
      <center><h1>Dr Yu-Hung Wu</h1>
      <h1>President</h1></center>
    </div>
      <div id="message">
        <p><strong style="font-size: 50px;">“</strong><br>On behalf of the Asian Society of Dermatopathology
        (ASD), we sincerely welcome you to join our 4th Annual
        Meeting on Oct 24-25, 2022. It’s our great pleasure and
        privileges to share the knowledge, experience, and
        updates of dermatopathology in this meeting. We
        deeply acknowledge all staffs and faculties for their
        great efforts and commitment to organize and present
        in this conference. We wish the convention every
        success and all the best to everyone.
        <br><br><br>Let me know if there is any question.
        <br><br>Best regards,<br><br>Yuhung</p>
        <strong id="right">„</strong>
      </div>

    <div id="for_blue"></div>
    <div id="for_yellow"></div>

    <div id="about">
      <center><h1>About the Asian Society of Dermatopathology (ASD)</h1></center>
    </div>

    <div id="asd">
      <img src="../../image/ASD_Logo.png">
    </div>

    <div id="message_asd">
      <p>The Asian Society of Dermatopathology (ASD) was founded in
      2016 by prominent Dermatologists and Dermatopathologists
      from the different recognized medical societies predominantly
      based in Southeast Asian countries. Apart from creating
      professional relationships, the goal of the society was to be
      able improve the caliber of this subspecialty and to hone
      further the diagnostic eye of its members by the sharing of
      cases and being up-to-date with the new developments in this
      field. The ASD offers Online Self-Learning Programs, monthly
      webinars, annual international meetings, and provides links to
      Asian dermatopathology fellowship and certification
        programs.</p><br><br>
      <center><a href="#" style="color: darkblue">Visit the ASD Website</a></center>
    </div>

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

    <div id="subscribe">
      <h1>SUSCRIBE TO OUR NEWSLETTER</h1>
      <input id="email" name="email" placeholder="Email" size="50px" style="margin-left: 250px; margin-top: 20px">
    </div>

    <div id="button_sub">
      </div>

    <div id="for_blue2"></div>
    <div id="for_bue2_mess"><p>2022 All Rights Reserved © Asian Society of Dermatopathology | October 24-25, 2022</p></div>
    <div id="for_yellow2"></div>
    </div>


</template>

<script>
import "../../css/style.css"
export default {
  name: 'HelloWorld',
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
      visible10: false
    }
  }
  }
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
</style>
