---
layout: default
title: Projects
permalink: /projects/
show_picture: false
---

<div style="background-color: rgb(174, 225, 252); padding: 5px; border-radius: 10px; box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1); margin-bottom: 20px;">
<h1 style="text-align:center; margin: 0;">Active Projects</h1>
</div>
<div style="display: flex; gap: 20px; align-items: flex-start;  background-color:#e0e0e0;box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1); border-radius: 10px; margin-bottom: 30px;">

  <!-- Left Block: Picture and Icons -->
  <div style="flex: 1; max-width: 350px; display: flex; justify-content: center; align-items: center; padding: 20px;">
    <img src="/assets/images/projects/net_design.png" alt="Your Image" style="max-width: 50%; max-height: 50%; border-radius: 10px;">
</div>

  <!-- Right Block: Text Content -->
  <div style="flex: 2; padding: 20px; border-radius: 10px;">
    <h2>
      Network Design
    </h2>
    <p>
      Many networks found in nature, such as proteins and molecules, are reproduced with exact connectivity patterns. Relying on mathematical tools such as Bayesian inference and graph theory, along with multiple datasets, we are investigating how nature is able to design network's with exact connectivity patterns.
    </p>
  </div>
</div>

<div style="display: flex; gap: 20px; align-items: flex-start;  background-color: #e0e0e0; box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1); border-radius: 10px; margin-bottom: 30px;">
<!-- Left Block: Picture and Icons -->
  <div style="flex: 1; max-width: 350px; display: flex; justify-content: center; align-items: center; padding: 20px;">
    <img src="/assets/images/projects/net_recon.png" alt="Your Image" style="max-width: 100%; max-height: 100%; border-radius: 10px;">
</div>

  <!-- Right Block: Text Content -->
  <div style="flex: 2; padding: 20px; border-radius: 10px;">
    <h2>
      Network Reconstruction
    </h2>
    <p>
      Network reconstruction seeks to reveal the hidden network structure of a system using it's node-level dynamics. State-of-the-art methods use Bayesian inference to detect these networks. We are investigating how these methods are biased as a result of the true, underlying structure of the network.
    </p>
  </div>
</div>

<div style="display: flex; gap: 20px; align-items: flex-start;  background-color: #e0e0e0; box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1); border-radius: 10px; margin-bottom: 30px;">
<!-- Left Block: Picture and Icons -->
  <div style="flex: 1; max-width: 350px; display: flex; justify-content: center; align-items: center; padding: 20px;">
    <img src="/assets/images/projects/net_recon.png" alt="Your Image" style="max-width: 100%; max-height: 100%; border-radius: 10px;">
</div>

  <!-- Right Block: Text Content -->
  <div style="flex: 2; padding: 20px; border-radius: 10px;">
    <h2>
      Network Entanglement
    </h2>
    <p>
      Physical networks are networks which take up volume in 3D-space. Our previous work introduced various measures of link entanglement in these networks. We are applying these measures to network materials to understand the effect entanglement has on the physical properties of a network.
    </p>
  </div>
</div>

<div style="background-color: #e0e0e0; box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1); border-radius: 10px; margin-bottom: 30px;">
  <!-- Dropdown Header -->
  <div style="cursor: pointer; padding: 20px; background-color: #d9d9d9; border-radius: 10px; display: flex; justify-content: space-between; align-items: center;" onclick="toggleDropdown('dropdown1')">
    <h3 style="margin: 0; text-align: left;">Network Design</h3>
    <span style="font-size: 20px;">&#9660;</span> <!-- Down arrow -->
  </div>

  <!-- Dropdown Content -->
  <div id="dropdown1" style="display: none; padding: 20px; gap: 10px;">
    <img src="/assets/images/projects/net_design.png" alt="Icon" style="width: 50px; height: 50px; border-radius: 5px;">
    <p style="margin:0;">
      Many networks found in nature, such as proteins and molecules, are reproduced with exact connectivity patterns. Relying on mathematical tools such as Bayesian inference and graph theory, along with multiple datasets, we are investigating how nature is able to design network's with exact connectivity patterns.
    </p>
  </div>
</div>

<div style="background-color: #e0e0e0; box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1); border-radius: 10px; margin-bottom: 30px;">
  <!-- Dropdown Header -->
  <div style="cursor: pointer; padding: 20px; background-color: #d9d9d9; border-radius: 10px;" onclick="toggleDropdown('dropdown1')">
    <h3 style="margin: 0;">Network Reconstruction</h3>
  </div>

  <!-- Dropdown Content -->
  <div id="dropdown1" style="display: none; padding: 20px;">
    <p>
      Network reconstruction seeks to reveal the hidden network structure of a system using its node-level dynamics. State-of-the-art methods use Bayesian inference to detect these networks. We are investigating how these methods are biased as a result of the true, underlying structure of the network.
    </p>
  </div>
</div>

<div style="background-color: #e0e0e0; box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1); border-radius: 10px; margin-bottom: 30px;">
  <!-- Dropdown Header -->
  <div style="cursor: pointer; padding: 20px; background-color: #d9d9d9; border-radius: 10px;" onclick="toggleDropdown('dropdown2')">
    <h3 style="margin: 0;">Network Entanglement</h3>
  </div>

  <!-- Dropdown Content -->
  <div id="dropdown2" style="display: none; padding: 20px;">
    <p>
      Physical networks are networks which take up volume in 3D-space. Our previous work introduced various measures of link entanglement in these networks. We are applying these measures to network materials to understand the effect entanglement has on the physical properties of a network.
    </p>
  </div>
</div>

<script>
  function toggleDropdown(id) {
    const element = document.getElementById(id);
    if (element.style.display === 'none') {
      element.style.display = 'block';
    } else {
      element.style.display = 'none';
    }
  }
</script>