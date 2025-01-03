<h3>My Work in ERIE Lab</h3>

<style>
    .image-overlay-container {
    position: relative;
    display: inline-block;
  }
  
  .image-overlay-container img {
    width: 100%; /* Ensure the image scales properly */
    height: auto;
    display: block;
  }
  
  .image-overlay-container .overlay-text {
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    color: white;
    text-align: center;
    opacity: 0;
    background: rgba(0, 0, 0, 0.5); /* Optional dark overlay for better text visibility */
    padding: 10px;
    border-radius: 10px;
    transition: opacity 0.3s ease;
  }
  
  .image-overlay-container:hover .overlay-text {
    opacity: 1; /* Text becomes visible on hover */
  }
</style>

<div class="image-overlay-container">
  {% include figure image_path="../haptic-enabled_switch_adapted_toys.jpg" alt="A Haptic-Enabled Switch Adapted Toy" %}
  <div class="overlay-text">
    Haptic-Enabled Switch Adapted Toys
  </div>
</div>