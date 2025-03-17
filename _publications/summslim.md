---
title: "SummSlim: A Universal and Automated Approach for Debloating Container Images"
collection: publications
permalink: /publication/summslim
excerpt: 'This paper is about container image slim.'
date: 2024-08-15
venue: 'ICPADS'
# slidesurl: 'https://www.acsac.org/2023/files/web/slides/xu-67-log2policy.pdf'
paperurl: 'https://www.computer.org/csdl/proceedings-article/icpads/2024/159600a132/22f0sZ3OxTG'
citation: 'Z. Zhang et al., "SummSlim: A Universal and Automated Approach for Debloating Container Images," in 2024 IEEE 30th International Conference on Parallel and Distributed Systems (ICPADS), Belgrade, Serbia, 2024, pp. 132-141, doi: 10.1109/ICPADS63350.2024.00027.'
---

Container technology has become a cornerstone of cloud computing, offering notable benefits such as enhanced resource utilization and streamlined deployment processes. The adoption of container technology by leading cloud service providers has steadily increased over the years. However, during the image construction phase, the reuse of base images and the execution of certain commands often results in the retention of redundant files, leading to resource wastage and potential security vulnerabilities. In this research, we systematically review and analyze existing methodologies, identify shortcomings in current approaches, and propose an automated image debloating tool named SummSlim according to the characteristics of the container image construction process. We selected 195 official images from Docker Hub for testing and evaluated the effectiveness of SummSlim with a success rate of $98.46 \%$. Then we compare and analyze the images before and after debloating, and make some novel suggestions for developers. To the best of our knowledge, SummSlim is the first practically available universal image debloating tool.