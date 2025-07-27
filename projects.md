---
layout: default
title: Projects
permalink: /projects/
show_picture: false
---

<!-- <div style="background-color: rgb(174, 225, 252); padding: 5px; border-radius: 10px; box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1); margin-bottom: 20px;"> -->
<h1 style="text-align:left; ">Active Projects</h1>
<hr style="width: 100%; border: 2px solid black; margin-top: 0px;">
<!-- </div> -->

<div style="background-color: #e0e0e0; box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1); border-radius: 10px; margin-bottom: 30px;">
  <!-- Header -->
  <div style="padding: 20px; background-color: #d9d9d9; border-radius: 10px; display: flex; align-items: center;">
    <h3 style="margin: 0; text-align: left;">Network Design</h3>
  </div>

  <!-- Content -->
  <div style="padding: 20px;">
    <div style="display: flex; align-items: center; gap: 20px;">
      <!-- Image -->
      <img src="/assets/images/projects/net_design.png" alt="Icon" style="width: 150px; height: 150px; border-radius: 5px;">
      
      <!-- Text -->
      <p style="margin: 0;">
        Many networks found in nature, such as proteins and molecules, are reproduced with exact connectivity patterns. Relying on mathematical tools such as Bayesian inference and graph theory, along with multiple datasets, we are investigating how nature is able to design networks with exact connectivity patterns.
      </p>
    </div>
  </div>
</div>

<div style="background-color: #e0e0e0; box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1); border-radius: 10px; margin-bottom: 30px;">
  <!-- Header -->
  <div style="padding: 20px; background-color: #d9d9d9; border-radius: 10px; display: flex; align-items: center;">
    <h3 style="margin: 0; text-align: left;">Network Reconstruction</h3>
  </div>

  <!-- Content -->
  <div style="padding: 20px;">
    <div style="display: flex; align-items: center; gap: 20px;">
      <!-- Image -->
      <img src="/assets/images/projects/net_recon.jpg" alt="Icon" style="width: 150px; height: 150px; border-radius: 5px;">
      <!-- Text -->
      <p style="margin: 0;">
        Network reconstruction seeks to reveal the hidden network structure of a system using its node-level dynamics. State-of-the-art methods use Bayesian inference to detect these networks. We are investigating how these methods are biased as a result of the true, underlying structure of the network.
      </p>
    </div>
  </div>
</div>

<div style="background-color: #e0e0e0; box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1); border-radius: 10px; margin-bottom: 30px;">
  <!-- Dropdown Header -->
  <div style="padding: 20px; background-color: #d9d9d9; border-radius: 10px; display: flex; align-items: center;">
    <h3 style="margin: 0; text-align: left;">Network Entanglement</h3>
  </div>

  <!-- Dropdown Content -->
  <div style="padding: 20px;">
    <div style="display: flex; align-items: center; gap: 20px;">
      <!-- Image -->
      <img src="/assets/images/projects/net_entanglement.png" alt="Icon" style="width: 150px; height: 150px; border-radius: 5px;">
      <!-- Text -->
      <p style="margin: 0;">
        Physical networks are networks which take up volume in 3D-space. Our previous work introduced various measures of link entanglement in these networks. We are applying these measures to network materials to understand the effect entanglement has on the physical properties of a network.
      </p>
    </div>
  </div>
</div>

<div style="background-color: #e0e0e0; box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1); border-radius: 10px; margin-bottom: 30px;">
  <!-- Dropdown Header -->
  <div style="padding: 20px; background-color: #d9d9d9; border-radius: 10px; display: flex; align-items: center;">
     <h3 style="margin: 0; text-align: left;">Brain Stimulation Targets for Depression</h3>
  </div>

  <!-- Dropdown Content -->
 <div style="padding: 20px;">
    <div style="display: flex; align-items: center; gap: 20px;">
     <!-- Image -->
      <img src="/assets/images/projects/brain_stimulation.png" alt="Icon" style="width: 150px; height: 150px; border-radius: 5px;">
      <!-- Text -->
      <p style="margin: 0;">
        Brain stimulation is an effective therapy for psychiatric illness, however which parts of the brain to stimulate for particular illnesses remains an open question. We seek to identify stimulation targets to improve depression symptoms in patients. 
      </p>
    </div>
  </div>
</div>

<script>
  function toggleDropdown(id) {
    const element = document.getElementById(id);
    if (element.style.display === 'none' || element.style.display === '') {
      element.style.display = 'block';
    } else {
      element.style.display = 'none';
    }
  }
</script>