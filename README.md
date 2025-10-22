<p align="left">
  <img src="https://avatars.githubusercontent.com/u/47839859?s=400&u=53725fcc96668470dd0cdd025c319ce5592b310f&v=4" alt="Profile Picture" width="180" style="border-radius: 50%; overflow: hidden;">
</p>

<a href="http://www.linkedin.com/in/zach-sanson" target="_blank">
  <img src="https://img.shields.io/badge/LinkedIn-blue?logo=linkedin&logoColor=white&style=for-the-badge" alt="LinkedIn - Zach Sanson" height="40">
</a>

## About Me

I'm an Automated Test Engineer at Tait Communications, specializing in creating test systems and simulated P25 radio equipment. My focus is on developing robust CI/CD tests, analyzing log and test results, and ensuring radio systems meet TIA specifications through low-level packet encoder development.

I collaborate closely with developers to test and verify new features, maintain and upgrade software packages, and ensure our systems conform to evolving standards. My work often involves simulating complex radio networks and automating test processes to enhance product reliability.

### Top Skills
<div>
  <img src="https://github.com/devicons/devicon/blob/master/icons/python/python-original.svg" title="Python" alt="Python" width="40" height="40"/>
  <img src="https://github.com/devicons/devicon/blob/master/icons/cplusplus/cplusplus-original.svg" title="C++" alt="C++" width="40" height="40"/>
  <img src="https://github.com/devicons/devicon/blob/master/icons/c/c-original.svg" title="C" alt="C" width="40" height="40"/>
  <img src="https://cdn.jsdelivr.net/gh/simple-icons/simple-icons/icons/influxdb.svg" title="InfluxDB" alt="InfluxDB" width="40" height="40"/>
  <img src="https://cdn.jsdelivr.net/gh/simple-icons/simple-icons/icons/grafana.svg" title="Grafana" alt="Grafana" width="40" height="40"/>
  <img src="https://github.com/devicons/devicon/blob/master/icons/docker/docker-original.svg" title="Docker" alt="Docker" width="40" height="40"/>
  <img src="https://cdn.jsdelivr.net/gh/simple-icons/simple-icons/icons/cucumber.svg" title="Cucumber" alt="Cucumber" width="40" height="40"/>
</div>

- **Python** – Daily driver; expert in automation, test systems, and scripting
- **C++** – Code review, debugging, and minor development
- **InfluxDB** – Storing and querying test result datasets
- **Grafana** – Visualizing data from InfluxDB in custom dashboards
- **Docker** – Creating, managing, and deploying containerized environments
- **Gherkin/Cucumber** – Designing readable BDD-style test steps that bridge human-friendly procedures to backend automation, ensuring test clarity and direct code integration

### Favourite Projects

- [**Custom Keyboard (southerly-split-keeb)**](https://github.com/WibblyGhost/southerly-split-keeb): Designed a split ergonomic keyboard from the ground up.  
  The layout was crafted using [ErgoGen](https://ergogen.cache.works/) in JavaScript, enabling customized ergonomic positioning. The PCB was designed as a multi-layer board, featuring complex circuitry for tight component placement and integrated addressable RGB lighting. I developed 3D-printed case designs in CAD, emphasizing tight tolerances and compactness, and iterated on several prototypes for optimal fit. Firmware was built from scratch using QMK in C, allowing for advanced key mapping and lighting control.  
  _See project README for further details on layout, PCB, case prototyping, and firmware._

- [**Solar Logger**](https://github.com/WibblyGhost/solar_logger): Multi-stage IoT solution for logging and visualizing solar power data.  
  The system interfaces with an Outback solar controller, subscribing to an MQTT backend that streams real-time statistics such as battery status and input voltages. Incoming MQTT data, broadcast as raw byte streams, is deciphered into human-readable values before being converted into time series data points. These points are then inserted into an InfluxDB instance, enabling efficient storage, modeling, and querying of historical solar data.  
  The application architecture is multi-threaded: one thread listens and processes MQTT packets while another uploads parsed data to InfluxDB, with queues facilitating communication between them. This ensures reliable, concurrent handling of data streams and database updates. The stored data is visualized via a private Grafana dashboard, providing detailed graphs and analytics for monitoring and comparison.  
  _See project README for architecture, hardware, and software insights._

- [**BitStructures**](https://github.com/WibblyGhost/BitStructures) (WIP): A Python library for defining structural codecs, making it easier to encode and decode packet designs at the bit level rather than byte level.

---

_Always eager to dive into new technologies, automate complex systems, and turn data into actionable insights!_