# JupyterLab3.github.io
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mastering JupyterLab</title>
    <style>
        /* Modern Reset & Variables */
        * {
            margin: 0;
            padding: 0;
            box-box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }
        :root {
            --bg-color: #0f172a;
            --card-bg: #1e293b;
            --accent-orange: #f97316;
            --accent-blue: #38bdf8;
            --text-main: #f8fafc;
            --text-muted: #94a3b8;
        }

        body {
            background-color: #1A365D;
            color: var(--text-main);
            line-height: 1.6;
        }

        /* Navbar */
        nav {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 1.5rem 10%;
            padding-bottom: 0px; 
            margin-bottom: 0px;
            background-color: rgba(15, 23, 42, 0.8);
            backdrop-filter: blur(10px);
            position: sticky;
            top: 0;
            z-index: 100;
        }
        .logo {
            font-size: 1.5rem;
            font-weight: bold;
            padding-bottom: 0px; 
            margin-bottom: 0px;
            color: var(--text-main);
        }
        .logo span {
            color: var(--accent-orange);
        }
        .nav-links a {
            color: var(--text-muted);
            text-decoration: none;
            margin-left: 2rem;
            transition: color 0.3s;
        }
        .nav-links a:hover {
            color: var(--accent-blue);
        }

        /* Hero Section */
        .hero {
            display: flex;
            align-items: center;
            justify-content: space-between;
            padding: 5rem 10%;
            min-height: 80vh;
        }
       .hero-content, [class*="hero"] {
          width: 100% !important;
           max-width: 950px !important; 
           margin: 0 auto !important;  
           padding: 40px 20px !important;
          text-align: left !important;  
        }

    .hero-content h1 {
         font-size: 3.5rem;
         line-height: 1.2;
         margin-bottom: 1.5rem;
        }

     .hero-content h1 span {
         color: var(--accent-orange);
       }
       .h1 {
       margin-top: 10px;
    }


     .hero-content p {
          font-size: 1.2rem;
         color: var(--text-muted);
         margin-bottom: 2rem;
         max-width: 800px; 
       }
       .btn {
        display: inline-block;
        background: linear-gradient(135deg, var(--accent-orange), #ea580c);
        color: white;
        padding: 0.8rem 2rem;
        border-radius: 5px;
        text-decoration: none;
        font-weight: bold;
        transition: transform 0.3s, box-shadow 0.3s;
    }
    .btn:hover {
        transform: translateY(-2px);
        box-shadow: 0 4px 20px rgba(249, 115, 22, 0.4);
    }
       
        /* Interactive Code Box Demo */
        .hero-visual {
            max-width: 45%;
            width: 100%;
        }
        .code-box {
            background-color: var(--card-bg);
            border-radius: 8px;
            padding: 1.5rem;
            box-shadow: 0 10px 30px rgba(0,0,0,0.5);
            border: 1px solid #334155;
        }
        .code-header {
            display: flex;
            gap: 0.5rem;
            margin-bottom: 1rem;
        }
        
        .code-input {
            color: var(--accent-blue);
            font-family: 'Courier New', Courier, monospace;
            margin-bottom: 1rem;
        }
        .code-output {
            background-color: #0f172a;
            padding: 1rem;
            border-radius: 4px;
            border-left: 4px solid var(--accent-orange);
            font-family: monospace;
        }

        /* Curriculum Section */
        .curriculum {
            padding: 5rem 10%;
            background-color: #0b111e;
        }
        .curriculum h2 {
            text-align: center;
            font-size: 2.5rem;
            margin-bottom: 3rem;
        }
        .grid,.row, [class*="card-container"], [class*="wrapper"]{
            display:flex !important;
            flex-direction: column !important;
            align-items: center !important;
            width: 100% !important; 
        }
        .card,[class*="box"], [class*="item"]{
            background-color: var(--card-bg);
            width: 100% !important;
            max-width: 800px !important;
            margin-bottom: 24px !important; 
            padding: 24px !important;
        }
        .card:hover {
            transform: translateY(-5px);
        }
        .card h3 {
            color: var(--accent-blue);
            margin-bottom: 1rem;
        }

        /* Footer */
        footer {
            text-align: center;
            padding: 2rem;
            color: var(--text-muted);
            border-top: 1px solid #1e293b;
        }

        /* Responsive Design */
        @media (max-width: 768px) {
            .hero {
                flex-direction: column;
                text-align: center;
                padding-top: 2rem;
            }
            .hero-content {
                max-width: 100%;
                margin-bottom: 3rem;
            }
            .hero-visual {
                max-width: 100%;
            }
            .nav-links {
                display: none; /* Keep it simple for mobile */
            }
    </style>
</head>
<body>
    <nav>
        <div class="logo">🚀 Learn<span>Jupyter</span></div>
    </nav>

    <section class="hero">
        <div class="hero-content">
            <a href="https://ayana-sarkar.github.io/Home2.github.io/" class="btn">Basic</a>
         <a href="https://ayana-sarkar.github.io/JupyterLab4.github.io/" class="btn">Plotting with List</a>
        <a href="https://ayana-sarkar.github.io/JupyterLab5.github.io/" class="btn">Plotting with Arrays</a>
        <a href="https://ayana-sarkar.github.io/JupyterLab2.github.io/" class="btn">Interpolation</a>
        <a href="https://ayana-sarkar.github.io/JupyterLab1.github.io/" class="btn">Special func</a>
        <a href="https://ayana-sarkar.github.io/JupyterLab3.github.io/" class="btn">Let's Practice more!</a>
        <h1>Let's Practice more!</h1>
        </div>
    </section>

    <section id="curriculum" class="curriculum">
            <div class="card">
            <h2> 1. Notice the difference b/w List and Arrays</h2>
            <img src="" alt="Data Visualization" class="box-image">
            </div>
            <div class="card">
                <h2>1.Identify the errors</h2>
                <img src="Screenshot 2026-06-09 141606.png" alt="Data Visualization" class="box-image">
                <p>Answers: <br> 
                Line2,3 : range should always be in ( ) , not { } . <br> 
                Line 3: wrong-- [i in range{1,100}] <br> 
                Right-- [i for i in range(1,100)]<br> 
                Line 4: there’s a typo error; x and X are not the same. <br></p>
                <img src="Screenshot 2026-06-09 141352.png" alt="Data Visualization" class="box-image">
            </div>
            <div class="card">
                <h2>2.Identify the errors </h2>
                <img src="Screenshot 2026-06-09 124840.png" alt="Data Visualization" class="box-image">
                <p>Answers:<br> 
                Line 4 :  the y array contains only 1 element that is 0, so no way any graph can be plotted. <br> 
                Line 5,6: JupyterLab cannot understand  --val1, val2 in (x,y)<br> 
                zip(x,y) is essential  to bring the values from x and y .<br> </p>
                <img src="Screenshot 2026-06-09 124745.png" alt="Data Visualization" class="box-image">
            </div>
            <div class="card">
                <h2>3. Plot the functions x, x 3 , e x and e x ^2 over the interval 0 < x < 4 using (i) rectangular paper (ii) semilog paper (iii)log-log paper. </h2>
                <img src="Screenshot 2026-03-15 110347.png" alt="Data Visualization" class="box-image">
                <img src="Screenshot 2026-03-15 110404.png" alt="Data Visualization" class="box-image">
                <img src="Screenshot 2026-03-15 110426.png" alt="Data Visualization" class="box-image">
                <p>plt.semilogy(x, y) plots data with a linear scale on the horizontal (x) axis and a logarithmic (base-10) scale on the vertical (y) axis. </p>
                <img src="" alt="Data Visualization" class="box-image">
                <img src="" alt="Data Visualization" class="box-image">
                <p>plt.loglog(x, y) : This creates a plot where both the x-axis and the y-axis are scaled logarithmically. </p>
                <img src="" alt="Data Visualization" class="box-image">
            </div>
            <div class="card">
                <h2>4.Population Graph</h2>
                <p>Plot the expression Pi(t), determined in modeling the growth of the population of a certain country according to two different models labelled by the parameters a1 and a2 given by<br> 
                Pi(t) = 197, 273, 000/(1 + eai (t-1913.25))  <br> 
                where t is the date, in years AD, using t = 1790 to 2000. What population is predicted 
                in the year 2020? The values of the parameters are a1 = -0.0313 (Swami) and a2 = -0.121 (Ghosh). Supply labels and legends for the graphs.<br></p>
                <img src="" alt="Data Visualization" class="box-image">
                <img src="" alt="Data Visualization" class="box-image">
                <p>predicted population in the year 2020 <br></p>
                <img src="" alt="Data Visualization" class="box-image">
            </div>
            <div class="card">
                <h2>5.Plot the Trajectory</h2>
                <p>Write a Python script using matplotlib to plot the height of the object over the first 5 seconds . Include a dashed horizontal line at h = 0 to clearly show the ground level. Use scipy.optimize.fsolve to numerically determine a time t when the object is at ground level (h(t) = 0), using an initial guess of tguess = 0.2.</p>
                <img src="" alt="Data Visualization" class="box-image">
                <p>The height of the object as a function of time t (represented as x in the code) is given by the kinematic equation: <br> 
                h(t) = vt – ½*gt^2<br> 
                plt.axhline(0) adds a horizontal line across the entire width of the  plot at a specific y-value. It tells the function to place the line at y = 0.<br> 
                x_guess = 0.2 Sets the starting point (initial guess) for the root-finding algorithm. Fsolve would start from 0.2 and "walk" along the curve until they find where it hits zero.<br> 
                fsolve(nonlinear_eq, x_guess): This calls SciPy's root finder. It takes the function (nonlinear_eq) and the starting point (0.2), does the mathematical heavy lifting, and returns the answer inside a NumPy array (e.g., [0.0]).<br>
                [0]: Because fsolve returns an array, adding [0] at the end grabs just the first number out of that array so x_solution becomes a clean, single float value (0.0) instead of a list.<br> 
                Isclose: Computers struggle with perfect precision due to floating-point math. Instead of checking if the result is exactly 0 (which might fail if the computer calculates 0.0000000000000001), np.isclose(..., 0) asks: "Is this number close enough to zero within a tiny fraction of a tolerance?" It evaluates to a boolean: True or False.</p>
                <img src="" alt="Data Visualization" class="box-image">
            </div>
            <div class="card">
                <h2>6.Normal Probability Density Function</h2>
                <p.>Write a Python script using scipy.stats.norm.pdf and matplotlib to plot the theoretical standard normal distribution (where the mean µ = 0 and standard deviation = 1 over the range [-4, 4]. Label the x-axis as 'Value', the y-axis as 'Density', title the plot 'Normal Distribution', and display a grid and a legend labeling the curve as 'Theoretical PDF'.</p>
                <img src="" alt="Data Visualization" class="box-image">
                <p>Line3:norm.pdf stands for the Normal Probability Density Function. It comes from the scipy.stats module (usually imported via from scipy.stats import norm)<br> 
                x: This is your input array of data points (created by your np.linspace(-4, 4, 200)). The function will calculate a density value for all 200 points between -4 and 4.<br> 
                loc=mu: This defines the mean (center) of your distribution. In your code, mu = 0, meaning the bell curve will be perfectly centered on 0.<br> 
                scale=sigma: This defines the standard deviation (width/spread) of your distribution. In your code, sigma = 1. A standard deviation of 1 means about 68% of all data points will fall between x = -1 and x = 1.<br></p>
                <img src="" alt="Data Visualization" class="box-image">
            </div>
            <div class="card">
                <h2>7. radioactive decay equations for the combined decay of a Parent and Daughter nuclei using an Euler algorithm.</h2>
                <img src="" alt="Data Visualization" class="box-image">
                <p>CELL 1:<br> 
                %matplotlib inline: A Jupyter Notebook magic command that ensures any plots generated will display directly inside the notebook rather than opening in a separate pop-up window.<br> 
                t = t0 Initializes a tracking clock variable t to the starting time.<br> 
                tVec = r_[t0:tmax:dt] Creates an array (a vector) of time steps from 0 to 5, spaced by 0.05. (Note: r_ is a NumPy shortcut, though standard practice usually uses np.arange(t0, tmax, dt)).<br> 
                NaVec = zeros(size(tVec)) & NbVec= zeros(size(tVec)) Creates empty arrays filled with zeros that are exactly the same length as tVec. These will act as data logs to hold the population values of A and B at every single time step. (Note: In modern NumPy, these would typically be written as np.zeros(...)).<br> 
                CELL 2: <br> 
                i= 0: Initializes an index counter to keep track of which slot in our storage arrays (NaVec, NbVec) we are currently writing to.<br> 
                for ti in tVec: Starts a loop that will run once for every single timestamp stored in tVec.<br> 
                NaVec[i] = Na & NbVec[i] = Nb: Saves the current population values of A and B into our data logs at the current index position i.<br> 
                Na = Na- (Na/Ta)*dt Calculates the new population of Parent A for the next time step using the differential equation dNA/dt = -NA\tauA. In code, it reads: New A = Old A minus the amount that decayed during this interval. <br> 
                Nb = Nb + ((Na/Ta) - (Nb/Tb))*dt Calculates the new population of Daughter B. Its change depends on two things: it gains whatever Parent A just lost (Na/Ta), and simultaneously loses its own atoms as it decays into a granddaughter isotope (Nb/Tb). <br> 
                i+=1:  Increments our index counter by 1 so that the next iteration of the loop saves its data into the very next slot of the arrays.<br> 
                CELL 3: <br> 
                rcParams['mattext.default']= 'regular':  Configures Matplotlib's math text rendering so that any LaTeX equations used in titles or labels match the regular font style of the graph rather than looking italicized.<br> 
                la=r'$\tau_{\mathrm{Parent}}$ = ' + str(Ta) &<br> lb=r'$\tau_{\mathrm{Daughter}}$ = ' + str(Tb):  Dynamically creates string labels for the graph legend. The r'$...$' structure allows Python to render raw LaTeX notation . It appends the lifetime values (1.0 and 2.0) to the labels.<br></p>
                <img src="" alt="Data Visualization" class="box-image">
            </div>
    </section>

</body>
</html>
