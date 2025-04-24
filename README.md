<?xml version="1.0" encoding="UTF-8"?>
<svg viewBox="0 0 1000 400" xmlns="http://www.w3.org/2000/svg">
  <foreignObject width="100%" height="100%">
    <div xmlns="http://www.w3.org/1999/xhtml">
      <style>
        .byReevenContainer {
          display: flex;
          flex-direction: column;
          align-items: center;
          justify-content: center;
          border-radius: 10px;
          width: 100%;
          background: #333;
          padding: 100px 0;
          font-family: system-ui, sans-serif;
        }

        .byReeven {
          display: flex;
          flex-direction: column;
          align-items: center;
          justify-content: center;
          text-align: center;
          height: 100px;
        }

        h1 {
          margin: 0;
          font-size: 5em;
          letter-spacing: 8px;
          font-family: "Lucida Console", monospace;
          font-weight: 400;
          line-height: 1em;
        }

        h1:nth-child(1) {
          color: #fff;
          animation: glitch1 2.5s infinite;
        }

        h1:nth-child(2) {
          color: #67f3da;
          animation: glitch2 2.5s infinite;
        }

        h1:nth-child(3) {
          color: #f16f6f;
          animation: glitch3 2.5s infinite;
        }

        @keyframes glitch1 {
          7% { transform: skew(-0.5deg, -0.9deg); opacity: 0.75; }
          30% { transform: skew(0.8deg, -0.1deg); opacity: 0.75; }
          55% { transform: skew(-1deg, 0.2deg); opacity: 0.75; }
          75% { transform: skew(0.4deg, 1deg); opacity: 0.75; }
        }

        @keyframes glitch2 {
          7% { transform: translate(-2px, -3px); opacity: 0.5; }
          30% { transform: translate(-5px, -2px); opacity: 0.5; }
          55% { transform: translate(-5px, -1px); opacity: 0.5; }
          75% { transform: translate(-2px, -6px); opacity: 0.5; }
        }

        @keyframes glitch3 {
          7% { transform: translate(2px, 3px); opacity: 0.5; }
          30% { transform: translate(5px, 2px); opacity: 0.5; }
          55% { transform: translate(5px, 1px); opacity: 0.5; }
          75% { transform: translate(2px, 6px); opacity: 0.5; }
        }
      </style>

      <div class="byReevenContainer">
        <div class="byReeven">
          <h1>Hey, I'm</h1>
          <h1>Hey, I'm</h1>
          <h1>Hey, I'm</h1>
        </div>
        <div class="byReeven">
          <h1>Juanjo!</h1>
          <h1>Juanjo!</h1>
          <h1>Juanjo!</h1>
        </div>
      </div>
    </div>
  </foreignObject>
</svg>

