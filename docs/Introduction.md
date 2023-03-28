
<link rel="stylesheet" href="/_/static/css/extra.css" type="text/css" />

<h1> Introduction </h1>

{%- if theme_light_logo and theme_dark_logo %}
<div class="sidebar-logo-container">
  <img class="sidebar-logo only-light" src="{{ pathto('_static/' + theme_light_logo, 1) }}" alt="Light Logo"/>
  <img class="sidebar-logo only-dark" src="{{ pathto('_static/' + theme_dark_logo, 1) }}" alt="Dark Logo"/>
</div>
{%- endif %}


Spiking Neural Networks (SNNs) are a type of artificial neural network that attempts to mimic the behavior of neurons in the brain. Unlike traditional neural networks that use continuous-valued signals, SNNs operate using discrete spikes of activity that are similar to the action potentials in biological neurons. SynapticFlow is a powerful Python package for prototyping and simulating SNNs. It is based on PyTorch and supports both CPU and GPU computation. SynapticFlow extends the capabilities of PyTorch and enables us to take advantage of using spiking neurons. Additionally, it offers different variations of synaptic plasticity as well as delay learning for SNNs.

Please consider supporting the SynapticFlow project by giving it a star ⭐️ on <a href="https://github.com/arsham-khoee/synapticflow">Github</a>, as it is a simple and effective way to show your appreciation and help the project gain more visibility.

If you encounter any problems, want to share your thoughts or have any questions related to training spiking neural networks, we welcome you to open an issue, start a discussion, or join our <a href="https://discord.gg/dhQyAMxM">Discord</a> channel where we can chat and offer advice.
<br>

<h3> Requirements </h3>
The requirements for SynapticFlow are as follows: 

<ul>
  <li>torch</li>
  <li>seaborn</li>
  <li>math</li>
</ul>