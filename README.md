# Attendance Mate

## Team Members
- Hrithik Mhatre (Civil Engineering, B.Tech., 3rd year)
- Mehul Agrawal (Civil Engineering, B.Tech., 3rd year)

## Project Overview
Attendance Mate aims to create a user-friendly, cost-effective, and accurate attendance tracking system using facial recognition technology. This project addresses the challenges of error-prone manual processes, proxy attendance, and lack of real-time tracking in educational environments.

## Problem Statement
- Error-prone manual attendance processes
- Issues related to proxy attendance and inaccuracy
- Lack of real-time tracking for attendance
- Non-streamlined daily activities, such as mess and reading hall attendance
- Need for an efficient and accurate attendance management system

## Proposed Solution
- Develop a Python-based facial recognition attendance system that is highly customizable.
- The system will mark attendance from photos captured within our app, utilizing various machine learning algorithms and facial recognition libraries for optimal results.
- The solution will be cost-effective as it does not require physical camera installations.
- The target audience includes students on campus who want to streamline the attendance marking process.

## Deployment Locations
- Classrooms
- Reading Halls
- Mess Areas
- Any Entrance/Exit Points

## Success Metrics
- **Accuracy Rate:** Percentage of correctly identified and recorded attendances.
- **Real-time Response Time:** Time taken for the system to register and reflect attendance changes.
- **User Adoption and Satisfaction:** Percentage of students actively using the mobile app for attendance marking.
- **Operational Efficiency:** Reduction in time and resources required for attendance management compared to traditional methods.

## Work Description
1. **Image Capture Pipeline:** Generated using Google Colab to capture and assess images for testing. [Colab Link](https://colab.research.google.com/drive/1CwRFTdMMSO7tiShFgHXa_mqwnxih1qWr?usp=sharing)
2. **Face Extraction and Embedding:**
   - YOLO for face extraction: [YOLO V8 Colab](https://colab.research.google.com/drive/1lwH6pUz-o7FRxxqSYAgUatsNkhYTag6I?usp=sharing)
   - MTCNN for face detection: [MTCNN Colab](https://colab.research.google.com/drive/1Mteo8sz1OehoxCDr4_ajPt07Y_DN80G-?authuser=)
3. **Siamese Network Training:** The embeddings of positive, anchor, and negative images are passed into the Siamese network using the Triplet loss function. [Siamese Network Colab](https://colab.research.google.com/drive/1Qg3VNibMj6gUrX1su-hyle2XLq54k6UM?usp=sharing)

## Future Plans
- Schedule a meeting with the SAFE Team and respective professors to enhance our model.
- Implement Face Image Quality Assessment to ensure high-performance face recognition.
- Create a dataset of student images to fine-tune the model.
- Acquire a GPU for model training.
- Seek collaboration for app development.

## Challenges
- Ensuring high accuracy in face recognition.
- Gathering a comprehensive dataset of student images.
- Developing an intuitive mobile application for attendance marking.

## Financial Overview
| Items           | Amount | Remarks   |
|------------------|--------|-----------|
| Funding Provided  | 0      |           |
| Balance           | 0      |           |

## Gantt Chart of Future Plans
- **March**: Talk with SAFE Team
- **April**: Understand OFIQ library and its usage
- **May**: Create and deploy the app that runs the model and verifies location

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments
- Special thanks to our mentors and peers for their support and guidance throughout this project.
