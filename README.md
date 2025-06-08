# Network-Intrusion-Detection-Datasets

This repository provides a collection of intrusion detection 
datasets reviewed in the ACM Computing Surveys paper titled 
"A Systematic Review on Graph-based Anomaly Detection: 
Approaches for Intrusion Detection." 
It summarizes publicly available datasets commonly used in 
graph-based anomaly detection (GBAD) research. 
Each dataset entry includes a brief description, the type of 
data (such as network traffic, host-based logs, or multi-modal 
inputs), the types of attacks included, and a direct link
to download the dataset from its official source. 
This compilation is intended to support researchers 
and practitioners by offering a structured and accessible 
reference point for datasets relevant to GBAD in cybersecurity.

## Network Datasets

Network datasets encompasses traffic information and activities across network infrastructure, including packet
flows and network logs, which are essential for intrusion detection monitoring.
They are widely used in intrusion detection tasks to detect threats such as DDoS, port scans, and spoofing based on communication patterns between hosts.

<table>
  <thead>
    <tr>
      <th style="width: 10%;">Dataset</th>
      <th style="width: 20%;">Attack/Anomalies</th>
      <th style="width: 50%;">Description</th>
      <th style="width: 20%;">Link</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>CICIDS</td>
      <td>DoS, DDoS, Web Attack, Infiltration, Port scan, Botnet</td>
      <td>Network traffic data provided in pcap and CSV formats, with extracted flow features</td>
      <td><a href="https://www.unb.ca/cic/datasets/ids-2017.html">Link</a></td>
    </tr>
    <tr>
      <td>UNSW-NB15</td>
      <td>Exploits, Reconnaissance, DoS, Generic, Shellcode, etc.</td>
      <td>Real benign and simulated attack traffic logs collected from simulation environments</td>
      <td><a href="https://research.unsw.edu.au/projects/unsw-nb15-dataset">Link</a></td>
    </tr>
    <tr>
      <td>LANL</td>
      <td>APT attacks</td>
      <td>1.6B+ events including authentication, network flow, DNS, and attack logs</td>
      <td><a href="https://csr.lanl.gov/data/cyber1/">Link</a></td>
    </tr>
    <tr>
      <td>CTU-13 Botnet</td>
      <td>Botnet</td>
      <td>Botnet traffic across 13 scenarios, 2.5M packets between 371K hosts</td>
      <td><a href="http://mcfp.weebly.com/">Link</a></td>
    </tr>
    <tr>
      <td>CICDDoS</td>
      <td>DDoS (TCP, UDP, Mixed types)</td>
      <td>Labeled network traffic data from various DDoS attack scenarios</td>
      <td><a href="https://www.unb.ca/cic/datasets/ddos-2019.html">Link</a></td>
    </tr>
    <tr>
      <td>Kyoto 2006+</td>
      <td>N/A</td>
      <td>3 years of honeypot traffic with over 93 million sessions</td>
      <td><a href="http://www.takakura.com/Kyoto_data/">Link</a></td>
    </tr>
    <tr>
      <td>Darknet</td>
      <td>N/A</td>
      <td>Traffic of audio, browsing, chat, video, P2P, etc. from CIC</td>
      <td><a href="https://www.unb.ca/cic/datasets/darknet2020.html">Link</a></td>
    </tr>
    <tr>
      <td>ToR-non Tor</td>
      <td>N/A</td>
      <td>Traffic data for seven scenarios comparing ToR and non-ToR</td>
      <td><a href="https://www.unb.ca/cic/datasets/tor.html">Link</a></td>
    </tr>
    <tr>
      <td>SUEE8</td>
      <td>Slowloris, Slowhttptest</td>
      <td>Traffic in/out of a web server over 8 days mixed with 150 attacks</td>
      <td><a href="https://github.com/vs-uulm/2017-SUEE-data-set?tab=readme-ov-file">Link</a></td>
    </tr>
    <tr>
      <td>AndMal2019 / EncMal2021</td>
      <td>Malwares</td>
      <td>Traffic from Android apps (AndMal), and 5M+ streams (EncMal)</td>
      <td><a href="https://www.unb.ca/cic/datasets/andmal2020.html">Link</a></td>
    </tr>
    <tr>
      <td>AWID-CLS-R</td>
      <td>Flooding, Impersonation, Injection</td>
      <td>MAC-layer traces for benign and malicious WLAN activities</td>
      <td><a href="https://www.kaggle.com/datasets/zhiqingcui/awidclsr">Link</a></td>
    </tr>
    <tr>
      <td>CERT</td>
      <td>Insider threats</td>
      <td>Logs of 100B+ behaviors from 4000 users</td>
      <td><a href="https://kilthub.cmu.edu/articles/dataset/Insider_Threat_Test_Dataset/12841247">Link</a></td>
    </tr>
    <tr>
      <td>IoT-23</td>
      <td>Botnet (Mirai, Okiru, etc.)</td>
      <td>23 IoT scenarios with benign and malicious traffic</td>
      <td><a href="https://mcfp.felk.cvut.cz/publicDatasets/IoT-23-Dataset/iot_23_datasets_small.tar.gz">Link</a></td>
    </tr>
    <tr>
      <td>MedBIoT</td>
      <td>Botnet, malware</td>
      <td>Labeled dataflows from medium-sized IoT networks</td>
      <td><a href="https://cs.taltech.ee/research/data/medbiot/">Link</a></td>
    </tr>
    <tr>
      <td>Bot-IoT, ToN-IoT, etc.</td>
      <td>Multiple IoT threats (DDoS, ransomware, etc.)</td>
      <td>Extensive IoT traffic datasets (network + telemetry) from UNSW and UQ</td>
      <td>
        <a href="https://research.unsw.edu.au/projects/bot-iot-dataset">Bot-IoT</a>, 
        <a href="https://staff.itee.uq.edu.au/marius/NIDS_datasets/">ToN-IoT</a>
      </td>
    </tr>
    <tr>
      <td>IOST</td>
      <td>Storm Botnet, Waledac</td>
      <td>Botnet traffic + benign traffic from various labs</td>
      <td><a href="https://onlineacademiccommunity.uvic.ca/isot/2022/11/27/botnet-and-ransomware-detection-datasets/">Link</a></td>
    </tr>
    <tr>
      <td>CAN Dataset</td>
      <td>DoS, Fuzzy, Replay, Spoofing</td>
      <td>40 CAN traffic logs from vehicles in controlled settings</td>
      <td><a href="https://ocslab.hksecurity.net/Datasets/can-signal-extraction-and-translation-dataset">Link</a></td>
    </tr>
  </tbody>
</table>

## Host Datasets
Host datasets comprises comprehensive information streams captured from individual computing systems, encompassing both kernel-level operating system interactions and high-level application operations. This data spectrum
extends from fundamental system calls and kernel operations to user-facing activities like shell commands,
application logs, and Windows event records. Such multifaceted data collection enables detailed analysis of
system operations, user behaviors, and the complex interactions between human operators and computing
resources, providing critical visibility into both machine-level processes and user-driven activities within the
system environment.

<table>
  <thead>
    <tr>
      <th style="width: 10%;">Dataset</th>
      <th style="width: 20%;">Attack/Anomalies</th>
      <th style="width: 50%;">Description</th>
      <th style="width: 20%;">Link</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>WUIL</td>
      <td>Data breaching</td>
      <td>File system access dataset including 3050 normal and 222 attack samples</td>
      <td>Unknown</td>
    </tr>
    <tr>
      <td>DARPA</td>
      <td>APT, Phishing, Dictionary attacks, FTP-write, Port scan</td>
      <td>IDS datasets with full packet captures, including the 1999 set, OpTC for APT activities, and E3/E5 engagement datasets simulating real-world APT scenarios</td>
      <td>
        <a href="https://www.ll.mit.edu/r-d/datasets/1999-darpa-intrusion-detection-evaluation-dataset">DARPA 1999</a>,
        <a href="https://www.ll.mit.edu/r-d/datasets/1998-darpa-intrusion-detection-evaluation-dataset">DARPA 1998</a>
      </td>
    </tr>
    <tr>
      <td>ATLAS</td>
      <td>APT attacks</td>
      <td>Labeled logs collected from a real-world system with 20,088 entities and 249K events per scenario</td>
      <td><a href="https://github.com/purseclab/ATLAS/tree/main/raw_logs">Link</a></td>
    </tr>
    <tr>
      <td>StreamSpot</td>
      <td>Drive-by download attack</td>
      <td>500 benign graphs across 5 scenarios and 100 attack graphs for 1 scenario, collected on Linux machines</td>
      <td><a href="https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/83KYJY">Link</a></td>
    </tr>
    <tr>
      <td>Unicorn</td>
      <td>APT (malware download, RCE, command injection)</td>
      <td>System provenance dataset collected using CamFlow over three days with 125 benign and 25 attack graphs. Includes SC-1 and SC-2 versions</td>
      <td><a href="https://github.com/margoseltzer/shellshock-apt">SC-2</a></td>
    </tr>
  </tbody>
</table>

## Multi-modal Datasets
Multi-modal datasets combine data from multiple sources—such as network traffic, host logs, and system events—to provide a holistic view of system behavior. They enable advanced anomaly detection by capturing both inter-host and intra-host interactions, supporting more robust detection of complex attack patterns.

<table>
  <thead>
    <tr>
      <th style="width: 15%;">Dataset</th>
      <th style="width: 20%;">Attack/Anomalies</th>
      <th style="width: 50%;">Description</th>
      <th style="width: 15%;">Link</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>DeepTraLog</td>
      <td>Service fault anomalies</td>
      <td>Consists of 132,485 traces and 7.7M log messages, where 17% of those are anomalous</td>
      <td><a href="https://github.com/FudanSELab/DeepTraLog/tree/main/TraceLogData">Link</a></td>
    </tr>
    <tr>
      <td>BETH</td>
      <td>Unusual/malicious activities</td>
      <td>Kernel-level process logs and network traffic</td>
      <td><a href="https://www.kaggle.com/datasets/katehighnam/beth-dataset">Link</a></td>
    </tr>
    <tr>
      <td>MSDS</td>
      <td>Anomalies</td>
      <td>Consists of traces, logs, and metrics from an OpenStack-distributed system</td>
      <td><a href="https://zenodo.org/record/3549604">Link</a></td>
    </tr>
    <tr>
      <td>AIOpsChallenge</td>
      <td>Service, Pod and Node anomalies</td>
      <td>Instance metrics and logs for 40 services on 6 servers in a microservice-based system</td>
      <td><a href="https://github.com/NetManAIOps/AIOps-Challenge-2020-Data">Link</a></td>
    </tr>
    <tr>
      <td>TraceRCA</td>
      <td>Anomalies</td>
      <td>Datasets with traces and metrics from microservice-based systems</td>
      <td><a href="https://github.com/NetManAIOps/TraceRCA">Link</a></td>
    </tr>
  </tbody>
</table>
