# Dense Visual Odometry and SLAM (dvo_slam)

*NOTE: this is an alpha release APIs and parameters are going to change in near future. No support is provided at this point.*

These packages provide an implementation of the rigid body motion estimation of an RGB-D camera from consecutive images.

 *  **dvo_core**
    
    Core implementation of the motion estimation algorithm. 
    
 *  **dvo_ros**
    
    Integration of *dvo_core* with ROS.
    
 *  **dvo_slam**
    
    Pose graph SLAM system based on *dvo_core* and integration with ROS.
    
 *  **dvo_benchmark**
    
    Integration of *dvo_slam* with TUM RGB-D benchmark, see http://vision.in.tum.de/data/datasets/rgbd-dataset.
    
 *  **sophus**
    
    ROS package wrapper for Hauke Strasdat's Sophus library (reverted to compliant commit), see https://github.com/bartville/Sophus.
    

## Installation

Checkout the branch for your ROS version into a folder in your `ROS_PACKAGE_PATH` and build the packages with `rosmake`.

 *  ROS Kinetic:
    
    ```bash
    git clone -b fuerte git://github.com/tum-vision/dvo_slam.git
    catkin_make
    ```

## Usage

Estimating the camera trajectory from an RGB-D image stream:


## Publications

The following publications describe the approach:

 *   **Dense Visual SLAM for RGB-D Cameras** (C. Kerl, J. Sturm, D. Cremers), In Proc. of the Int. Conf. on Intelligent Robot Systems (IROS), 2013.
 *   **Robust Odometry Estimation for RGB-D Cameras** (C. Kerl, J. Sturm, D. Cremers), In Proc. of the IEEE Int. Conf. on Robotics and Automation (ICRA), 2013
 *   **Real-Time Visual Odometry from Dense RGB-D Images** (F. Steinbruecker, J. Sturm, D. Cremers), In Workshop on Live Dense Reconstruction with Moving Cameras at the Intl. Conf. on Computer Vision (ICCV), 2011.

## License

The packages *dvo_core*, *dvo_ros*, *dvo_slam*, and *dvo_benchmark* are licensed under the GNU General Public License Version 3 (GPLv3), see http://www.gnu.org/licenses/gpl.html.

The package *sophus* is licensed under the MIT License, see http://opensource.org/licenses/MIT.
