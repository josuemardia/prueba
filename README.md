<svg>
  <rect x="50" y="50" width="100" height="100">
    <animateTransform 
      attributeType="xml"
      attributeName="transform"
      type="rotate"
      from="0 100 100"
      to="360 100 100"
      dur="2s"
      repeatCount="indefinite"/>
  </rect>
</svg>
<svg width="500" height="100">
  <style>
    @keyframes typing {
      from { width: 0; }
      to { width: 13em; }
    }
    @keyframes blink-caret {
      from, to { border-color: transparent; }
      50% { border-color: black; }
    }
    text {
      font-size: 2em;
      font-family: Arial, sans-serif;
      border-right: .15em solid black;
      animation: typing 3s steps(30, end), blink-caret .5s step-end infinite;
    }
  </style>
  <text x="50" y="70">Hola soy Josué</text>
</svg>


