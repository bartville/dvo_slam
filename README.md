# Dense Visual Odometry

I've forked DVO to use it in my [srrg_dvo_wrapper](https://gitlab.com/srrg-software/srrg_dvo_wrapper).

SLAM pipeline compilation is disabled, since I only needed Visual odometry functions and the SLAM pipeline has to be fixed for g2o compilation issues.

## Prerequisites 

ROS package wrapper for Hauke Strasdat's Sophus library (reverted to compliant commit), see https://github.com/bartville/Sophus.
    

## Installation

Put it in your Kinetic catkin workspace and compile.

## Publications of the Authors from TUM University

The following publications describe the approach:

 *   **Dense Visual SLAM for RGB-D Cameras** (C. Kerl, J. Sturm, D. Cremers), In Proc. of the Int. Conf. on Intelligent Robot Systems (IROS), 2013.
 *   **Robust Odometry Estimation for RGB-D Cameras** (C. Kerl, J. Sturm, D. Cremers), In Proc. of the IEEE Int. Conf. on Robotics and Automation (ICRA), 2013
 *   **Real-Time Visual Odometry from Dense RGB-D Images** (F. Steinbruecker, J. Sturm, D. Cremers), In Workshop on Live Dense Reconstruction with Moving Cameras at the Intl. Conf. on Computer Vision (ICCV), 2011.

## License

The packages *dvo_core*, *dvo_ros*, *dvo_slam*, and *dvo_benchmark* are licensed under the GNU General Public License Version 3 (GPLv3), see http://www.gnu.org/licenses/gpl.html.

The package *sophus* is licensed under the MIT License, see http://opensource.org/licenses/MIT.
