<style>
    .hover-image {
      position: relative;
      display: inline-block;
      border-radius: 15px; /* Makes the image edges rounded */
      overflow: hidden; /* Ensures the image doesn't overflow its container */
    }

    .hover-image img {
      display: block;
      width: 100%; /* Ensures the image fits its container */
      height: auto;
      transition: opacity 0.3s ease, transform 0.3s ease; /* Smooth transition */
      border-radius: 15px; /* Match the container rounding */
    }

    .hover-image .hover-text {
      position: absolute;
      bottom: 10%;
      left: 50%;
      transform: translateX(-50%);
      color: black;
      font-size: 16px;
      font-weight: bold;
      text-decoration: none; /* Initially no underline */
      opacity: 0;
      transition: opacity 0.3s ease, text-decoration 0.3s ease;
    }

    .hover-image:hover img {
      opacity: 0.5; /* Decrease opacity on hover */
      transform: scale(1.05); /* Slightly zoom the image for effect */
    }

    .hover-image:hover .hover-text {
      opacity: 1; /* Make text visible */
      text-decoration: underline; /* Add underline */
    }
</style>
<div class="hover-image">
    <img src="haptic-enabled_switch_adapted_toys.jpg" alt="Image of Switch Adapted Toy">
    <span class="hover-text">Haptic-Enabled Switch Adapted Toys</span>
</div>