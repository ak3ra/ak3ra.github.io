---
layout: post
title: WhoAmI
permalink: /about/
content-type: eg
---

<div class="biography">
<table class="biobox disable-select">
<tbody>
<tr>
<th colspan="2" style="text-align: center; font-size: 110%; font-weight: bold">
<div style="display: inline;">Benjamin Akera</div>
</th>
</tr>
<tr>
<td colspan="2" style="text-align: center">
<img id="profpic" src="/assets/img/akera.jpg"/>
<div id="profpicDesc" class="very-small">Portrait from <i>LinkedIn</i>, 2020</div><br>
</td>
</tr>
<tr>
<th scope="row">Alma mater</th>
<td><a href="https://mak.ac.ug/"><i>Makerere University</i></a></td>
</tr>
<tr>
<th scope="row">Main Interests</th>
<td>AI For Social Good, Deep Learning,  Natural Language Processing, Reinforcement Learning</td>
</tr>
<tr>
<th scope="row">Supervisors</th>
<td>Yoshua Bengio, Kris Sankaran, Dianbo Liu</td>
</tr>
</tbody>
</table>
</div>

<span style="font-size:180%; font-style: italic;">B</span>enjamin Akera <span style="font-size: 10px"> </span> is a machine learning research engineer currently at the <a href = "https://www.mila.quebec">Montreal Quebec AI Institute (MILA)</a> under the supervision of Prof. Yoshua Bengio. 

My areas of interest include computer vision, Natural language Processing and deep reinforcement learning with a focus on applications to societal good.

You can reach out to me directly at [[akeraben@gmail.com::mailto:akeraben@gmail.com]].

<hr>

### Talks

<em> - to be added </em>
<!-- | Name                   |                                                                                |
| ---------------------- | ------------------------------------------------------------------------------ |
| `_layouts`             | Replace all. Apply edits if you customized any layouts.                        |
| `_includes`            | Replace all. Apply edits if you customized any includes.                       |
| `assets`               | Replace all. Apply edits if you customized stylesheets or scripts.             |
| `_sass`                | Replace all. Apply edits if you customized Sass partials.                      |
| `_data/navigation.yml` | Safe to keep. Verify that there were no major structural changes or additions. |
| `_data/text.yml`       | Safe to keep. Verify that there were no major structural changes or additions. |
| `_config.yml`          | Safe to keep. Verify that there were no major structural changes or additions. | -->



### Papers

<em> - Some of them are on my Google scholar page </em>



<script>
const profilePics = {
   1: '/assets/img/profile.png',
   2: '/assets/img/profile.png'
}

Object.freeze(profilePics);

document.getElementById("profpic").addEventListener("click", function() {
   var iSrc = document.getElementById("profpic");
   var iSrcDesc = document.getElementById("profpicDesc");
   if (iSrc.src.match(profilePics[2])) {
      iSrc.src = profilePics[1];
      iSrcDesc.innerHTML = "v2";
   } else {
      iSrc.src = profilePics[2];
      iSrcDesc.innerHTML = "Portrait from <i>LinkedIn</i>, 2020";
   }
});

document.getElementById("profpic").addEventListener("contextmenu", function(e) {
   e.preventDefault();
   return false;
});


</script>