<h2>My Work in ERIE Lab</h2>

<a href="/target-page-url" class="mm-hover-container">
  {% include figure popup=true image_path="../haptic-enabled_switch_adapted_toys.jpg" alt="this is a placeholder image" caption="This is a figure caption." %}
  <span class="mm-hover-text">Click Here</span>
</a>

<style>
  .mm-hover-container {
    position: relative;
    display: inline-block;
    text-decoration: none; /* Removes default underline */
  }

  .mm-hover-container img {
    display: block;
    transition: opacity 0.3s ease; /* Smooth fade effect */
  }

  .mm-hover-container .mm-hover-text {
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    color: var(--mm-color-text-light); /* Light text color from theme */
    font-size: 1.2rem; /* Relative font size from Minimal Mistakes */
    font-weight: var(--mm-font-weight-bold); /* Theme's bold weight */
    opacity: 0;
    transition: opacity 0.3s ease; /* Smooth text fade effect */
    text-shadow: 0 1px 3px rgba(0, 0, 0, 0.8); /* Subtle shadow for better visibility */
  }

  .mm-hover-container:hover img {
    opacity: 0.7; /* Light fade on hover */
  }

  .mm-hover-container:hover .mm-hover-text {
    opacity: 1; /* Text appears on hover */
  }
</style>