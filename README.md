# awesome invariant-and-equivariant filter-and-observer

Paper list for invariant and equivariant filter and observer. Work-in-progress. 

Feel free to suggest relevant papers in the following format. 

```markdown
**Non-linear state error based extended Kalman filters with applications to navigation**  
Axel Barrau, PhD thesis, 2015 [paper](https://pastel.archives-ouvertes.fr/tel-01344622)   
```

*Acknowledgement*: I would like to thank [**Silvère Bonnabel**][http://www.silvere-bonnabel.com/Publications.html], [Tarek Hamel][https://dblp.uni-trier.de/pid/41/1354.html], [Jochen Trumpf][http://users.cecs.anu.edu.au/~trumpf/], [Pieter van Goor][https://pvangoor.github.io/],  for paper suggestions! 

**model-based nonlinear estimation methods**.  

### [Invariant Observer](#content)

1. **Nonlinear State Estimation and Modeling of a Helicopter UAV** 
   
   Martin Barczyk,  PhD thesis, 2012
   
   Note: **employing** a rotation matrix representation for the state manifold to obtain designs amenable to global stability analysis, **obtaining** a direct nonlinear design for gains of the AHRS observer, **modifying** the previously-proposed Invariant EKF systematic method for computing gains, and **culminating** in simulation and experimental validation of the observers.  
   
2. **Features of Invariant Extended Kalman Filter Applied to Unmanned Aerial Vehicle Navigation**

   Nak Yong Ko, Wonkeun Youn, In Ho Choi, Gyeongsub Song and Tae Sik Kim. sensors 2018. [paper][https://www.mdpi.com/1424-8220/18/9/2855]

3. **Optimal Invariant Observers Theory for Nonlinear State Estimation**

   Jean-Philippe Condomines,  Cédric Seren,  Gautier Hattenberger. [paper][http://recherche.enac.fr/~jean-philippe.condomines/wp-content/uploads/2015/12/IUKF16_book_chapter.pdf]

4. **Nonlinear Kalman Filtering for Multi-Sensor Navigation of Unmanned Aerial Vehicles**

   Jean-Philippe Condomines, Book 2018.

   Note: Invariant-UKF and $\pi$-IUKF. These two methods apply the general framework of **invariant observers** to the nonlinear estimation of the state of a dynamic system using an Unscented Kalman Filter (UKF) method, from the more general class of Sigma Point (SP) nonlinear filtering algorithms.    

5. **Augmented invariant-EKF designs for simultaneous state and disturbance estimation**

   Kevin Coleman, Master thesis, 2020 [paper][https://www.proquest.com/docview/2493158725/D51863A194EF4C31PQ/1?accountid=15157]

   Note: study Invariant-EKF designs for invariant systems with **disturbances**. Three different IEKF designs are presented for **a unicycle robot** under linear disturbances.   

### Invariant Filter

1. **Non-linear state error based extended Kalman filters with applications to navigation**  
   Axel Barrau, PhD thesis, 2015 [paper](https://pastel.archives-ouvertes.fr/tel-01344622)

   Note: Using the fact that the Jacobians are state-independent, it can be shown that the IEKF is **a locally asymptotically stable observer**, no matter the trajectory.  

2. **Smoothing algorithms for navigation, localisation and mapping based on high-grade inertial sensors**

   Paul Chauchat  , PhD thesis, 2020 [paper](https://pastel.archives-ouvertes.fr/tel-02887295)

3.  **Deep learning, Inertial Measurements Units, and Odometry: Some Modern Prototyping Techniques for Navigation Based on Multi-Sensor Fusion** 

   Martin Brossard  , PhD thesis, 2020 [paper](https://pastel.archives-ouvertes.fr/tel-03262132v1)

4. **Invariant smoothing on Lie groups**

   P. Chauchat, A. Barrau, and S. Bonnabel.  IROS 2018. [paper][https://ieeexplore.ieee.org/document/8594068]

   Note: leverage ideas from the IEKF framework, where the Jacobians are state independent, to create an IEKF-based SWF (ISWF), and demonstrate its robustness relative to IEKFs and traditional batch-estimation frameworks.  

5. **Invariant Sliding Window Filtering for Attitude and Bias Estimation**

   Alex Walsh;Jonathan Arsenault;James Richard Forbes.  2019 [paper][https://ieeexplore.ieee.org/document/8814702/]

   Note:  further study the ISWF  and apply it to non-group-affine process models.  

6. **An Invariant Extended $H_{\infty}$ Filter**  

   M. Lavoie, J. Arsenault, and J. R. Forbes. CDC2019 [paper][https://ieeexplore.ieee.org/document/9029289/]

7. **The Invariant Rauch-Tung-Striebel Smoother** 

   Niels van der Laan , Mitchell Cohen , Jonathan Arsenault , and James Richard Forbes.   IEEE Robotics and automation letters. 2020 [paper][https://ieeexplore.ieee.org/document/9126191]

8. **Robust Linearly Constrained Invariant Filtering for a Class of Mismatched Nonlinear Systems**

   Paul Chauchat, Jordi Vilà-Valls, Eric Chaumette. IEEE Control Systems Letters 2021 [paper][https://ieeexplore.ieee.org/document/9373652]

   Note: using linear constraints is an effective way to robustify the KF.   InEKF should be all the more sensitive to a possible system model mismatch.   

### [Theory](#content)

1. **Kalman filtering with a class of geometric state equality constraints**

   P. Chauchat, A. Barrau, S. Bonnabel.   CDC 2017. [paper][https://ieeexplore.ieee.org/document/8264033]

2. **Extended Kalman Filtering With Nonlinear Equality Constraints: A Geometric Approach**

   Axel Barrau, Silvère Bonnabel. IEEE Transactions on Automatic Control 2020. [paper][https://ieeexplore.ieee.org/document/8765615]

3. **Linear observed systems on groups**

   Axel Barrau, Silvère Bonnabel. Systems and Control Letters  2019. [paper][https://www.sciencedirect.com/science/article/pii/S0167691119300805]

4. **Equivariant Filter Design for Kinematic Systems on Lie Groups**

   Robert Mahony, Jochen Trumpf. MTNS2020 [paper][https://arxiv.org/abs/2004.00828]

   Note: invariant system --> group affine system --> equivariant system

5. **Equivariant Systems Theory and Observer Design**

   Robert Mahony, Tarek Hamel, Jochen Trumpf. [paper][https://arxiv.org/abs/2006.08276]

   Note: A discussion of invariant errors for systems with homogeneous state that motivates an observer/filter architecture with the observer state posed on the symmetry group.  

6. **A bundle framework for observer design on smooth manifolds with symmetry** 

   Anant A. Joshi, D.H.S. Maithripala, Ravi N. Banavar.  [paper][https://arxiv.org/abs/1907.09234]

   Note: the special case when the group action is free is given special emphasis  

### [Equivariant Filter](#content)

1. **A Geometric Nonlinear Observer for Simultaneous Localisation and Mapping**

   Robert Mahony, Tarek Hamel. CDC 2017

2. **Attitude Observation for Second Order Attitude Kinematics**  
     Yonhon Ng, Pieter van Goor, Robert Mahony, Tarek Hamel. CDC 2019 [paper](https://arxiv.org/abs/2104.06596)  
       Note: 

3. **Equivariant Systems Theory and Observer Design for Second Order Kinematic Systems on Matrix Lie Groups**  
     Yonhon Ng, Pieter van Goor, Tarek Hamel, Robert Mahony.  CDC 2020 [paper](https://arxiv.org/abs/2105.04797)  
       Note: 

4. **A Geometric Observer Design for Visual Localization and Mapping**

     Pieter van Goor, Robert Mahony, Tarek Hamel, Jochen Trumpf. CDC 2019 [paper][https://arxiv.org/pdf/1904.02452.pdf]

5. **An Observer Design for Visual Simultaneous Localisation and Mapping with Output Equivariance**

     Pieter van Goor, Robert Mahony, Tarek Hamel, Jochen Trumpf.  IFAC 2020 [paper][https://arxiv.org/abs/2005.14347]

6. **Constructive Observer Design for Visual Simultaneous Localisation and Mapping**

     Pieter van Goor, Robert Mahony, Tarek Hamel, Jochen Trumpf.  Submitted to Automatica  [paper][https://arxiv.org/abs/2006.05053]

7. **Equivariant Filter (EqF): A General Filter Design for Systems on Homogeneous Spaces**  
     Pieter van Goor, Tarek Hamel and Robert Mahony   CDC 2020  [paper][https://ieeexplore.ieee.org/abstract/document/9303813] [presentation][https://pvangoor.github.io/talks/2021/05/07/cdc2020_talk.html] [YouTube][https://www.youtube.com/watch?v=AwlDJU_3nuc]

8. **EQUIVARIANT FILTER (EqF)**  
     Pieter van Goor, Tarek Hamel and Robert Mahony [paper](https://arxiv.org/abs/2010.14666)

     Note: In cases where the system output is also equivariant the EqF leads to linearised dynamics with a constant output matrix.  

9. **Equivariant Visual Odometry in the Wild** 

     Robert Mahony, Pieter van Goor, Mina Henein, Ryan Pike, Jun Zhang and Yonhon Ng. CDC 2020

10. **An Equivariant Filter for Visual Inertial Odometry**  
     Pieter van Goor, Robert Mahony ICRA 2021 [paper](https://arxiv.org/abs/2104.03532) [Code][https://github.com/pvangoor/eqf_vio] [presentation][https://pvangoor.github.io/talks/2021/03/17/ardupilot_vio.html] [YouTube][https://www.youtube.com/watch?v=vLZdBKRjRi4]

     Note: The Equivariant Filter for Visual Inertial Odometry.


### [Application](#content)
#### Inertial-integrated navigation

1. **Contact-Aided Invariant Extended Kalman Filtering for Legged Robot State Estimation** 

   [code][GitHub - UMich-BipedLab/Contact-Aided-Invariant-EKF: Example code for contact-aided invariant extended Kalman filtering.]

2. **Contact-Aided Invariant Extended Kalman Filtering for Robot State Estimation**

   Ross Hartley , Maani Ghaffari , Ryan M Eustice and Jessy W Grizzle. IJRR 2020.  

3. **$SE_2(3)$ based Extended Kalman Filtering and Smoothing Framework for Inertial-Integrated Navigation** 

   Yarong Luo, Chi Guo, Jingnan Liu. [paper][https://arxiv.org/abs/2102.12897]

4. **Equivariant Filtering Framework for Inertial-Integrated Navigation**

   Yarong Luo, Chi Guo, Jingnan Liu. [paper][https://arxiv.org/abs/2103.14873]

5. **Legged Robot State Estimation in Slippery Environments Using Invariant Extended Kalman Filter with Velocity Update**

   Sangli Teng, Mark Wilfried Mueller, Koushil Sreenath. [paper][https://arxiv.org/abs/2104.04238]

#### SLAM

1. **Practical Considerations and Extensions of the Invariant Extended Kalman Filtering Framework**

    Jonathan Arsenault. Master thesis, 2019.  

    Note：Invariant Filtering in Continuous Time  and Discrete Time.

2. **Toward Invariant Visual-Inertial State Estimation using Information Sparsification**

    Shih-Chieh (Jerry) Hsiung. Master thesis, 2018. 

3. **Associating Uncertainty to Extended Poses for on Lie Group IMU Preintegration with Rotating Earth**

    M. Brossard, A. Barrau, P. Chauchat, S. Bonnabel. IEEE Transactions on Robotics 2021. [paper][https://arxiv.org/abs/2007.14097v2]

4. **A Mathematical Framework for IMU Error Propagation with Applications to Preintegration**

    Martin Brossard, Axel Barrau, Paul Chauchat, and Silvere Bonnabel. ICRA 2020. [paper][https://ieeexplore.ieee.org/document/9197492]  

5. **Consistent EKF-based visual-inertial odometry on matrix Lie group**

6. **Consistent EKF-based visual-inertial navigation using points and lines**

7. **Observability analysis and consistency improvements for visual-inertial odometry on the matrix Lie group of extended poses**

8. **Observability Analysis of IMU Intrinsic Parameters in Stereo Visual-Inertial Odometry**

9. **Consistent Right-Invariant Fixed-Lag Smoother with Application to Visual Inertial SLAM**

10. 



