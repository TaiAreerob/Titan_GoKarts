cmake_minimum_required(VERSION 3.0.2)
project(roboteq_nonholonomic_msgs)


find_package(catkin REQUIRED COMPONENTS message_generation std_msgs)

add_message_files(FILES
                  Duplex.msg
                  OdometryCovariances.msg
                  Point.msg
                  Vector3.msg
                  Quaternion.msg
                  Pose.msg
                  Twist.msg
                 )

add_service_files(FILES
                  RequestParam.srv
                  RequestOdometryCovariances.srv
                 )

generate_messages(DEPENDENCIES std_msgs)
catkin_package(CATKIN_DEPENDS message_runtime std_msgs)
