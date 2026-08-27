<script>
  export let size = 64;
  export let color = "#000";
  export let accent = "#ffcc00";
</script>

<svg
  width={size}
  height={size}
  viewBox="0 0 64 64"
  xmlns="http://www.w3.org/2000/svg"
>
  <!-- Body -->
  <ellipse cx="32" cy="36" rx="16" ry="20" fill={color} />

  <!-- Belly -->
  <ellipse cx="32" cy="38" rx="10" ry="14" fill="#ffffff" />

  <!-- Head -->
  <circle cx="32" cy="20" r="12" fill={color} />

  <!-- Eyes (closed, laughing) -->
  <path
    d="M26 18 q2 -2 4 0"
    stroke="#ffffff"
    stroke-width="2"
    fill="none"
    stroke-linecap="round"
  />
  <path
    d="M34 18 q2 -2 4 0"
    stroke="#ffffff"
    stroke-width="2"
    fill="none"
    stroke-linecap="round"
  />

  <!-- Laughing mouth -->
  <path
    d="M26 22 q6 6 12 0"
    stroke={accent}
    stroke-width="3"
    fill="none"
    stroke-linecap="round"
  />

  <!-- Beak (small accent under mouth) -->
  <path
    d="M29 24 q3 2 6 0"
    stroke={accent}
    stroke-width="2"
    fill="none"
    stroke-linecap="round"
  />

  <!-- Feet -->
  <ellipse cx="26" cy="52" rx="4" ry="2" fill={accent} />
  <ellipse cx="38" cy="52" rx="4" ry="2" fill={accent} />

  <!-- Flippers (slightly up like laughing) -->
  <path
    d="M18 34 q-4 -4 -2 -10"
    stroke={color}
    stroke-width="4"
    stroke-linecap="round"
    fill="none"
  />
  <path
    d="M46 34 q4 -4 2 -10"
    stroke={color}
    stroke-width="4"
    stroke-linecap="round"
    fill="none"
  />
</svg>
