## AR Multi-user Environments using Point Cloud Matching

I am developing a novel multi-user AR app that uses point cloud matching techniques and networking in ARFoundation to enable real-time object spawning across platforms (Mac OS, Android, Windows), and head-mounted display devices like Microsoft Hololens and Apple Vision Pro. I plan to conduct user research to examine the app's application in classroom settings, with support from NSF funding.

### Skills applied:
C#, Unity, AR Foundation, Mirror Networking, Computer Graphics techniques

### Challenge:
Given the rising demand for multi-user AR environments in fields like education, neuroscience, healthcare, and remote collaboration, there is a notable lack of research and open-source technologies that support spatial collaboration across users. This gap exists due to challenges such as platform incompatibility and the difficulty of managing spatial location information across different systems.

### Solution:
"ARClassroom" is an open-source AR application designed to address the challenge of spatial collaboration across platforms. By leveraging the Iterative Closest Point (ICP) technique from computer graphics, ARClassroom enables users to join a shared AR environment seamlessly, regardless of the platform they are using. The application is developed using ARFoundation for augmented reality experiences and Mirror for networking, ensuring smooth communication between users. At its core, ARClassroom employs the ICP technique to align and integrate users' spatial data in real-time. We use KD-Trees to enhance the app’s ability to collect and manage users' location data, making spatial collaboration in multi-user AR environments both more feasible and effective.


### What I learned:
- ARFoundation and AR Development: I learned how to create an AR application from scratch, including setting up the wireframe and developing the app infrastructure.
- Experimentation with Computer Graphics techniques: Through this project, I gained hands-on research experience with computer graphics techniques, particularly the Iterative Closest Point (ICP) algorithm and KD-Trees. These techniques were crucial for aligning and managing spatial data within the AR environment.

