<h1>3D Sierpinski Triangle Fractal</h1>
<p>This project generates a 3D fractal based on a tetrahedron, utilizing recursion and fractal geometry. The fractal is visualized using the <strong>Three.js</strong> library and displays a complex 3D structure made of triangles. Some of the triangles are filled with white color, while others are black, depending on their orientation. The black triangles create visual "holes" within the fractal, producing a dynamic, rotating 3D object.</p>

<h2>Features</h2>
 <ul>
        <li>Generates a 3D Sierpinski fractal based on a tetrahedron structure.</li>
        <li>Uses recursion to break the tetrahedron into smaller tetrahedrons.</li>
        <li>Inverted triangles (black) create holes, and the correct triangles (white) fill the structure.</li>
        <li>The fractal rotates around the Y-axis for dynamic visualization.</li>
        <li>Automatic adjustment of the fractal to fit the window size on resize.</li>
    </ul>

<h2>How It Works</h2>
    <p>The script starts by creating a tetrahedron. It then recursively divides the tetrahedron into smaller pieces, generating triangles at each step. The orientation of each triangle is checked, and if a triangle is inverted, it is colored black. Non-inverted triangles are colored white. The fractal rotates continuously around the Y-axis to create a smooth animation effect.</p>

<h3>Step-by-Step Process</h3>
    <ol>
        <li><strong>Scene Initialization</strong>: Creates the scene, camera, and renderer using <strong>Three.js</strong>.</li>
        <li><strong>Fractal Generation</strong>: A recursive function divides the initial tetrahedron into smaller tetrahedrons, generating triangles at each step.</li>
        <li><strong>Triangle Orientation Check</strong>: Each triangle's orientation is checked, and it is colored either white (correct orientation) or black (inverted orientation).</li>
        <li><strong>Rendering</strong>: The triangles are rendered and added to the scene.</li>
        <li><strong>Animation</strong>: The fractal is rotated on the Y-axis for dynamic visualization.</li>
    </ol>

 <h2>Getting Started</h2>
    <p>To run the project, follow these steps:</p>
    <ol>
        <li>Clone the repository to your local machine:</li>
        <pre><code>git clone https://github.com/x-ored/sierpinski-triangle-js.git</code></pre>
        <li>Open the project folder and open <code>fractal.html</code> in your web browser.</li>
    </ol>

 <h2>Prerequisites</h2>
    <p>This project requires <strong>Three.js</strong> for rendering the 3D fractal. The library is included in the script tag in the HTML file, so no additional installation is needed.</p>

 <h2>Credits</h2>
    <p>The fractal generation algorithm is based on the recursive division of a tetrahedron into smaller sub-tetrahedrons, creating a Sierpinski-like structure. The 3D rendering is powered by the <a href="https://threejs.org/">Three.js</a> library.</p>
 
