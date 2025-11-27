# Technical Overview

## System Components

### Sensor Network

**Sensor Types:**
1. **Mechanical Switches**
   - Purpose: Threshold-based detection
   - Function: Binary alert when water reaches specific level
   - Advantages: Low cost, reliable, no power required
   - Use case: Emergency flood alerts

2. **Optical Sensors/Diodes**
   - Purpose: Continuous water level measurement
   - Function: Precise depth readings
   - Advantages: High accuracy, real-time data
   - Use case: Trend analysis and prediction

<img width="653" height="381" alt="image" src="https://github.com/user-attachments/assets/d0b0b130-d0f2-4bc9-9873-695ba777476d" />

<img width="553" height="436" alt="image" src="https://github.com/user-attachments/assets/ac025045-db8f-46b7-a1df-d2b10c4f82d3" />


### Communication Architecture

**Publish-Subscribe Model:**
- Sensors publish data to message broker
- Dashboard and mobile app subscribe to data streams
- Decoupled architecture for scalability
- Real-time message distribution
- Uses the Information Service Bus Model (ISBM) 

### Data Processing (using ISBM module)

**Edge Computing Layer:**
- Local data validation and filtering
- Immediate alert generation
- Reduced network bandwidth
- Faster response times

**Cloud Processing:**
- Data aggregation and storage
- Historical analysis
- System-wide coordination

<img width="461" height="589" alt="image" src="https://github.com/user-attachments/assets/b9902414-ab47-4024-a8a5-3a0a17bc2970" />

<img width="581" height="581" alt="image" src="https://github.com/user-attachments/assets/cfb97d9b-757c-4a41-b575-c5eb4bd6e818" />

## Standards Compliance

### OIIE (Open Industrial Interoperability Ecosystem)

The system implements OIIE standards for:
- Data format standardization
- Interoperable communication protocols
- Vendor-neutral architecture
- Future extensibility


## Performance Metrics

- **Latency**: Sub-second alert generation
- **Reliability**: 100.0% uptime during field study
- **Data Volume**: 25,000+ measurements over 7 weeks
- **Sensor Coverage**: Multiple locations across campus

## Field Deployment

**Location:** University of Alabama campus  
**Duration:** 7 weeks  
**Environment:** Real-world flood-prone areas  
**Outcome:** Successful validation of system design

<img width="361" height="396" alt="image" src="https://github.com/user-attachments/assets/2725b930-f193-4482-aea4-e12eb5055689" />

## Research Outcomes

1. Demonstrated feasibility of low-cost IoT for flood monitoring
2. Validated standards-based interoperability approach
3. Proved effectiveness of edge computing for alerts
4. Established scalability for city-wide deployment

## Future Work

- Integration with city emergency systems
- Machine learning for flood prediction
- Extended sensor network coverage
- Enhanced mobile application features
