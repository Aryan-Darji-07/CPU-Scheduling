<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CPU Scheduling Simulator</title>
    <style>
        /* Add your CSS styles here */
    </style>
</head>
<body>
    <header>
        <h1>CPU Scheduling Simulator</h1>
        <p>The CPU Scheduling Simulator is a web-based application designed to help users understand and compare different CPU scheduling algorithms. With an intuitive user interface, users can input arrival times and burst times of processes and select from various scheduling algorithms to see how each one handles task execution.</p>
    </header>

    <section>
        <h2>Features</h2>
        <ul>
            <li><strong>User-Friendly Interface:</strong> The application provides a simple and intuitive interface for users to input process details and select scheduling algorithms.</li>
            <li><strong>Algorithm Selection:</strong> Users can choose from a range of CPU scheduling algorithms, including First Come First Serve (FCFS), Shortest Job First (SJF), Shortest Remaining Time First (SRTF), and Round Robin (RR).</li>
            <li><strong>Interactive Visualization:</strong> The simulator generates an interactive Gantt chart to visualize the scheduling sequence, allowing users to observe how processes are executed over time.</li>
            <li><strong>Output Analysis:</strong> After running the simulation, the application displays detailed output, including finish times, turnaround times, and waiting times for each process, as well as average turnaround and waiting times.</li>
            <li><strong>GitHub Integration:</strong> The project includes a link to the GitHub repository for easy access to the source code and collaboration.</li>
        </ul>
    </section>

    <section>
        <h2>Technologies Used</h2>
        <ul>
            <li>HTML: Structuring the web page layout and content.</li>
            <li>CSS: Styling the appearance of the web page and components.</li>
            <li>JavaScript: Implementing the CPU scheduling algorithms and interactivity.</li>
            <li>jQuery: Simplifying DOM manipulation and event handling.</li>
            <li>dotLottie: Integrating Lottie animations for visual appeal.</li>
            <li>GitHub: Hosting the project repository for version control and collaboration.</li>
        </ul>
    </section>

    <section>
        <h2>Usage</h2>
        <ol>
            <li>Clone the repository to your local machine.</li>
            <li>Open <code>index.html</code> in a web browser.</li>
            <li>Input arrival times and burst times of processes.</li>
            <li>Select a scheduling algorithm from the dropdown menu.</li>
            <li>Click the "Solve" button to run the simulation.</li>
            <li>View the output table and Gantt chart to analyze the scheduling results.</li>
        </ol>
    </section>

    <section>
        <h2>Contributing</h2>
        <p>Contributions are welcome! If you have any ideas for improvements or new features, feel free to open an issue or submit a pull request.</p>
    </section>

    <footer>
        <h2>License</h2>
        <p>This project is licensed under the MIT License.</p>
    </footer>
</body>
</html>
