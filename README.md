<h1>📡 Packet Sniffer Tool (Python)</h1>

<p>This project is a basic <strong>Packet Sniffer</strong> tool developed in Python. It captures live network traffic and displays important information such as <strong>source and destination IP addresses</strong>, <strong>protocols</strong>, and <strong>payload data</strong>.</p>

<h2>🔍 Features</h2>
<ul>
  <li>Captures network packets in real-time</li>
  <li>Extracts and displays source & destination IP addresses</li>
  <li>Identifies protocols used (TCP, UDP, ICMP, etc.)</li>
  <li>Shows raw payload data</li>
</ul>

<h2>⚙️ How It Works</h2>
<p>The tool uses <code>socket</code> programming and raw sockets to intercept packets. It then parses the headers and payload to reveal protocol-level information. This is useful for understanding how data travels across networks and for cybersecurity learning.</p>

<h2>📁 Output</h2>
<p>Details printed to the terminal include:</p>
<ul>
  <li><code>Source IP</code></li>
  <li><code>Destination IP</code></li>
  <li><code>Protocol Type</code></li>
  <li><code>Payload (raw data)</code></li>
</ul>

<h2>⚠️ Ethical Usage Notice</h2>
<p><strong>Warning:</strong> This tool is intended strictly for educational use or for testing in environments you own or have permission to analyze. Unauthorized network monitoring is unethical and may be illegal under cybersecurity and privacy laws.</p>

<h2>🚀 How to Run</h2>
<ol>
  <li>Ensure Python 3 is installed</li>
  <li>Run with administrative/root privileges (required to access raw sockets)</li>
  <li>Execute the script: <code>sudo python3 packet_sniffer.py</code></li>
</ol>

<h2>📚 Requirements</h2>
<ul>
  <li>Python 3.x</li>
  <li>No external packages required (uses built-in <code>socket</code> and <code>struct</code> libraries)</li>
</ul>

<h2>🧠 Learning Objectives</h2>
<ul>
  <li>Understand the structure of TCP/IP packets</li>
  <li>Learn how to work with raw sockets in Python</li>
  <li>Explore real-time packet analysis techniques</li>
</ul>

<h2>👨‍💻 Author</h2>
<p>Developed by likith N | For cybersecurity learning and ethical hacking practice</p>
