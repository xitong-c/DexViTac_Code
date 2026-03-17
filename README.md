# DexViTac_Code



This is the official codebase for DexViTac.The complete codebase will be released in the near future.

<img width="13760" height="4825" alt="figure1_01" src="https://github.com/user-attachments/assets/98112848-833a-41d6-818a-6101de0c351e" />

**Overview of DexViTac.** DexViTac is a portable, human-centric data collection system designed for contact-rich dexterous
manipulation. It enables the high-fidelity acquisition of first-person vision, high-density tactile sensing, and hand kinematics within
unstructured, in-the-wild environments, facilitating the development of generalized robotic policies across diverse hardware platforms.

## Abstract

Large-scale, high-quality multimodal demonstrations is essential for the robot learning of contact-rich dexterous manipulation. While human-centric data collection systems lower the barrier to scaling, they struggle to capture the tactile information during physical interactions. Motivated by this, we present DexViTac, a portable, human-centric data collection system tailored for contact-rich dexterous manipulation. The system enables the high-fidelity acquisition of first-person vision, high-density tactile sensing, end-effector poses, and hand kinematics within unstructured, in-the-wild environments. Building upon this hardware, we propose a kinematics-grounded tactile representation learning algorithm that effectively resolves semantic ambiguities within tactile signals. Leveraging the efficiency of DexViTac, we construct a multimodal dataset comprising over 2,400 visuo-tactile-kinematic demonstrations. Exprienments demonstrate that DexViTac achieves a collection efficiency exceeding 248 demonstrations per hour and remains robust against complex visual occlusions. Real-world deployment confirms that policies trained with the proposed dataset and learning strategy achieve an average success rate exceeding 85\% across four challenging tasks. This performance significantly outperforms baseline methods, thereby validating the substantial improvement the system provides for learning contact-rich dexterous manipulation.
