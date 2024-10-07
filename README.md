# Task-Priority Control Notes

A summary of works regarding task-priority control and underwater
vehicle-manipulator systems.

View and Download: [main.pdf](https://raw.githubusercontent.com/haakonbaa/task-priority-control-notes/main/build/main.pdf) <br>
View in browser:   [main.pdf](https://github.com/haakonbaa/task-priority-control-notes/blob/main/build/main.pdf)

## Overview

| year | Author                        | r | s | f | w | Title                 |
|------|-------------------------------|---|---|---|---|-----------------------|
| 1969 | Whitney                       |   | x | x |   | Resolved Motion Rate Control of Manipulators and Human Prostheses |
| 1981 | Hanafusa, Yoshikawa, Nakamura |   | x | x |   | Analysis and control of articulated robot arms with redundancy |
| 1987 | Nakamura et al.               |   | x | x |   | Task Priority Based Redundancy Control of Robot Manipulators |
| 1987 | Khatib                        | x | x |   |   | A unified approach for motion and force control of robot manipulators |
| 1991 | Siciliano et al.              | x | x |   |   | A General Framework For Managing Multiple Tasks in Highly Reduntant Robotic Systems |
| 1997 | Chiaverini                    | x | x | x | x | Singularity-robust task-priority redundancy resolution. |
| 2004 | Khatib                        | x | x | x | x | Whole-Body Dynamic Behavior and Control of Human-like Robots |
| 2005 | Sentis, Khatib                | x | x |   |   | Synthesis of whole-body behaviours through hierarchical control of behavioural primitives |
| 2005 | Nakanishi et al.              |   | x | x |   | Comparative Experiments on Task Space Control with Redundancy Resolution |
| 2009 | Antonelli                     | x | x | x |   | Stability Analysis for Prioritized Closed-Loop Inv |
| 2015 | Dietrich                      | x |   |   |   | An overview of null space projections for reduntant, torque-controlled robots |
| 2018 | Antonelli                     | x |   |   |   | Modeling Errors Analysis in Inverse Dynamics Appro |
| 2020 | Basso                         |   | x |   |   | Task-Priority Control of Redundant Robotic Systems using CL- and CB-Fs based QPs |
| 2022 | Iversflaten                   | x |   |   |   | Kinematic and Dynamic Control of Cooperating Under |
| 2023 | Iversflaten                   | x |   |   |   | Task-Priority Operational Space Control for Vehicle | 
| 2023 | Iversflaten                   | x |   |   |   | MSc. - Robust Task-Priority Control of Underwater Vehicle-Manipulator Systems |
| 2021 | Sæbø                          | x |   |   |   | Project Thesis |
| 2023 | Sæbø                          | x |   |   |   | MSc. Null Space-Based Control and Simulation of Vehicle-Manipulator Systems |
| 2019 | Basso                         | x |   |   |   | Project Thesis - Set-Based Task Priority Control for Articulated Intervention AUVs |
| 2018 | Schmidt-Didlaukies            | x | x |   |   | Modeling of Underwater Snake Robots, draft |
| 2018 | Schmidt-Didlaukies            | x | x |   |   | Modeling of Articulated Underwater Robots for Simulation and Control |

**r** *reccomended*,
**s** *started reading*,
**f** *finished reading*,
**w** *summary written*

## Sources

[hanafusa1981] **H. Hanafusa, T. Yoshikawa, and Y. Nakamura**, *“Analysis and Control of Articulated Robot Arms with Redundancy,”* IFAC Proceedings Volumes, vol. 14, no. 2, pp. 1927–1932, Aug. 1981, issn: 14746670. doi: [10.1016/S1474-6670(17)63754-6](https://doi.org/10.1016/S1474-6670(17)63754-6). Accessed: Sep. 10, 2024. [Online]. Available: <https://linkinghub.elsevier.com/retrieve/pii/S1474667017637546>.

[nakamura1987] **Y. Nakamura, H. Hanafusa, and T. Yoshikawa**, *“Task-Priority Based Redundancy Control of Robot Manip-ulators,”* The International Journal of Robotics Research, vol. 6, no. 2, pp. 3–15, Jun. 1987, issn: 0278-3649,1741-3176. doi: [10.1177/027836498700600201](https://doi.org/10.1177/027836498700600201). [Online]. Available: <https://journals.sagepub.com/doi/10.1177/027836498700600201>.

[khatib1987] **O. Khatib**, *“A unified approach for motion and force control of robot manipulators: The operational space formulation,”* IEEE Journal on Robotics ad Automation, vol. 3, no. 1, pp. 43–53, Feb. 1987, issn: 0882-4967. doi: [10.1109/jra.1987.1087068](https://doi.org/10.1109/jra.1987.1087068). [Online]. Available: <http://ieeexplore.ieee.org/document/1087068/>.

[chiaverini1997] **S. Chiaverini**, *“Singularity-robust task-priority redundancy resolution for real-time kinematic control of robot manipulators,”* IEEE Transactions on Robotics and Automation, vol. 13, no. 3, pp. 398–410, Jun. 1997, issn: 1042296X. doi: [10.1109/70.585902](https://doi.org/10.1109/70.585902). Accessed: Sep. 10, 2024. [Online]. Available: <http://ieeexplore.ieee.org/document/585902/>.

[khatib2004] **O. Khatib, L. Sentis, J. Park, and J. Warren**, *“WHOLE-BODY DYNAMIC BEHAVIOR AND CONTROL OF HUMAN-LIKE ROBOTS,”* International Journal of Humanoid Robotics, vol. 01, no. 01, pp. 29–43, Mar. 2004, issn: 0219-8436, 1793-6942. doi: [10.1142/S0219843604000058](https://doi.org/10.1142/S0219843604000058). Accessed: Sep. 10, 2024. [On-line]. Available: <https://www.worldscientific.com/doi/abs/10.1142/S0219843604000058>.

[sentis2005] **L. Sentis and O. Khatib**, *“SYNTHESIS OF WHOLE-BODY BEHAVIORS THROUGH HIERARCHICAL CONTROL OF BEHAVIORAL PRIMITIVES,”* International Journal of Humanoid Robotics, vol. 02, no. 04, pp. 505–518, Dec. 2005, issn: 0219-8436, 1793-6942. doi: [10.1142/S0219843605000594](https://doi.org/10.1142/S0219843605000594). Accessed: Sep. 10, 2024. [Online]. Available: <https://www.worldscientific.com/doi/abs/10.1142/S0219843605000594>.

[schmidtdidlaukies2018] **H. M. Schmidt-Didlaukies, A. J. Sorensen, and K. Y. Pettersen**, *“Modeling of Articulated Underwater Robots for Simulation and Control,”* in 2018 IEEE/OES Autonomous Underwater Vehicle Workshop (AUV), Porto, Portugal: IEEE, Nov. 2018, pp. 1–7, isbn: 978-1-72810-253-5. doi: [10.1109/AUV.2018.8729806](https://doi.org/10.1109/AUV.2018.8729806). Accessed: Sep. 10, 2024. [Online]. Available: <https://ieeexplore.ieee.org/document/8729806/>.
