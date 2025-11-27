<img width="1943" height="576" alt="project-smart-cities" src="https://github.com/user-attachments/assets/08383a13-4aae-4310-84e2-8667bed915b2" />

# Smart Cities and IoT Resilience Systems

[![Research Project](https://img.shields.io/badge/Status-Research%20Complete-success)](https://github.com/crumeike/smart-cities-iot)
[![Published](https://img.shields.io/badge/Publication-TISDIC%202023-blue)](https://iopscience.iop.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

Real-time flood monitoring and decision support system for urban infrastructure resilience using IoT sensors and edge computing.

**Note:** This repository documents a completed research project (2021-2023). See [Related Repositories](#related-repositories) for implementation code.

## 🎯 Overview

This project implemented an intelligent sensing and decision-support framework for urban flood monitoring. The system integrated IoT sensors with edge computing capabilities to provide real-time environmental monitoring and early warning alerts for flood events.

### Key Features

- **Real-time Monitoring**: Continuous water level tracking using low-cost IoT sensors
  - Mechanical switches for threshold detection
  - Optical sensors for precise water level measurement
- **Edge Computing**: Local data processing for rapid response
- **Standards-Based Architecture**: Built on OIIE (Open Industrial Interoperability Ecosystem) specifications
- **Decision Support Dashboard**: Interactive visualization for emergency response coordination
- **Mobile Alerts**: Real-time flood notifications via mobile application
- **Scalable Design**: Supports city-scale deployment

## 📊 Project Highlights

- **25,000+ data points** collected across 7-week field study
- **Real-time processing** with sub-second latency
- **OIIE standards** integration for interoperability
- **Mobile-first** alert system
- **Two sensor types**: Mechanical switches and optical sensors
- Deployed at **University of Alabama campus**

## 🏗️ System Architecture

```
┌─────────────────────────┐
│  IoT Sensors            │  
│  • Mechanical Switches  │  ← Water level detection
│  • Optical Sensors      │  
└────────┬────────────────┘
         │
         ▼
┌─────────────────┐
│ Edge Computing  │  ← Local processing
└────────┬────────┘
         │
         ▼
┌─────────────────┐
│ Cloud Server    │  ← Data aggregation
└────────┬────────┘
         │
         ├──────────────┬─────────────┐
         ▼              ▼             ▼
   ┌─────────┐   ┌──────────┐  ┌──────────┐
   │Dashboard│   │Mobile App│  │  Alerts  │
   └─────────┘   └──────────┘  └──────────┘
```

<img width="968" height="380" alt="image" src="https://github.com/user-attachments/assets/0ccd5a92-0136-4307-be07-2e06ac9777b9" />

<img width="938" height="497" alt="image" src="https://github.com/user-attachments/assets/06e478e8-fd42-4298-be68-bc89fab4d858" />

## 🛠️ Technologies Used

- **Hardware**: 
  - Mechanical switch sensors (threshold detection)
  - Optical sensors (precise measurement)
  - Low-cost IoT devices
- **Edge Computing**: Real-time data processing
- **Backend**: Python, C#
- **Standards**: OIIE (Open Industrial Interoperability Ecosystem)
- **Visualization**: Plotly dashboards
- **Mobile**: Flutter framework (Dart)
- **Communication**: Publish-Subscribe messaging

## 📈 Results

- Successfully monitored flood-prone areas in real-time
- Reduced alert latency from minutes to seconds
- Demonstrated scalability for city-wide deployment
- Published at **TISDIC 2023** international conference

<img width="628" height="607" alt="image" src="https://github.com/user-attachments/assets/d287db6a-148f-4a35-8ae7-68a36582bd6b" />

## 📝 Publications

**Conference Paper:**
> C. R. Umeike, X. Guo, T. Dao, S. Croope, X. Hong, and A. T. Johnston, "A Standards-based Approach to Enhancing Interoperability of Low-cost Industrial IoT Flood Sensors for Transportation System Resilience," *IOP Conference Series: Materials Science and Engineering*, vol. 1289, no. 1, p. 012022, Aug. 2023.

[View Publication](https://iopscience.iop.org/article/10.1088/1757-899X/1289/1/012022)

## 🏆 Recognition

- **First Place Innovation Award** - University of Alabama (2022)
- Published at **TISDIC 2023** International Conference (Da Nang, Vietnam)
- Featured in university smart campus initiative

## 📂 Repository Contents

This repository contains:
- Research documentation
- System architecture diagrams
- Technical specifications
- Project overview and results

## 🔗 Related Repositories

Implementation code for specific system components:

- **Decision Support System** - [Decision-Support-System](https://github.com/crumeike/Decision-Support-System) (C#)
- **Work Management System** - [WorkManagementSystem](https://github.com/crumeike/WorkManagementSystem) (C#)

## 🎓 Research Team

**Principal Investigator:**
- Dr. Silvana Croope, University of Alabama

**Faculty Advisor:**
- Dr. Thang Dao, University of Alabama
- Xiaoyan Hong
- Alan T Johnston

**Lead Researcher:**
- Robinson Umeike
- Xiaoming Guo

**Collaborators:**
- Vic Zhong
- Aaron Schofield


## 💡 Project Funding

**Funding Agency:** Alabama Department of Transportation (ALDOT)

**Institution:** University of Alabama, Department of Civil, Construction, and Environmental Engineering

## 📱 System Components

### Sensor Network
- Mechanical switches for threshold-based alerts
- Optical sensors for continuous water level measurement
- Edge computing nodes for local processing

### Dashboard
- Real-time data visualization
- Alert management interface
- Historical trend analysis
- Geospatial mapping

### Mobile Application
- Push notifications for flood alerts
- Live sensor data streams
- Historical data access
- Sensor health monitoring

## 🌐 Technical Approach

### OIIE Standards Integration
The system implements OIIE (Open Industrial Interoperability Ecosystem) specifications to ensure:
- Interoperability with external systems
- Standards-based data exchange
- Scalable architecture
- Future-proof design

### Publish-Subscribe Architecture
- Decoupled sensor-to-server communication
- Real-time data streaming
- Scalable message distribution
- Fault-tolerant design

## 🤝 Contributing

This is a completed research project. For questions or collaboration opportunities, please contact:

**Chibuike Robinson Umeike**  
Email: chibuikeumeike@gmail.com  
[Google Scholar](https://scholar.google.com/citations?user=IeJsfl8AAAAJ) | [LinkedIn](https://www.linkedin.com/in/chibuike-robinson-umeike-b57b1a183/)

## 📄 License

MIT License - see [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- **Funding**: Alabama Department of Transportation (ALDOT)
- **Institution**: University of Alabama, Department of Civil, Construction, and Environmental Engineering
- **Principal Investigator**: Dr. Silvana Croope
- **Advisor**: Dr. Thang Dao

## 📞 Contact

For questions about this research:

- **Email**: chibuikeumeike@gmail.com
- **LinkedIn**: [Chibuike Robinson Umeike](https://www.linkedin.com/in/chibuike-robinson-umeike-b57b1a183/)
- **Website**: [Personal Website]

## 📚 Citation

If you reference this work, please cite:

```bibtex
@inproceedings{umeike2023standards,
  title={A Standards-based Approach to Enhancing Interoperability of Low-cost Industrial IoT Flood Sensors for Transportation System Resilience},
  author={Umeike, Chibuike Robinson and Guo, Xiaobing and Dao, Thang and Croope, Silvana and Hong, Xiaobing and Johnston, Andrew T},
  booktitle={IOP Conference Series: Materials Science and Engineering},
  volume={1289},
  number={1},
  pages={012022},
  year={2023},
  organization={IOP Publishing}
}
```

---

**Project Status**: Research Completed (2021-2023)  
**Field Deployment**: University of Alabama Campus  
**Conference**: TISDIC 2023, Da Nang, Vietnam  
**Publication**: IOP Conference Series: Materials Science and Engineering
