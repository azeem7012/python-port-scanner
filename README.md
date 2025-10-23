 Simple Python Port Scanner

A lightweight, multi-threaded TCP **port scanner** written in Python.  
This project is for learning and authorized testing only.

 Features
 Multi-threaded scanning for speed
 Accepts port ranges or comma-separated lists
 Command-line options for threads and timeout

 Requirements
 Python 3.8+

 Usage
bash
basic example
python src/port_scanner.py --target 192.168.1.10 --ports 1-1024 --threads 100

scan specific ports
python src/port_scanner.py -t example.com -p 22,80,443
