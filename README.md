# LineageOS
LineageOS 系统定制

## 与AOSP对应关系
Android 14			LineageOS 21					</br>
Android 13			LineageOS 20					</br>
Android 12			LineageOS 19					</br>
Android 11			LineageOS 18					</br>
Android 10			LineageOS 17					</br>
Android 9			  LineageOS 16					</br>
Android 8			  LineageOS 15    LineageOS 15.1			</br>
Android 7			  LineageOS 14					</br>
Android 6			  LineageOS 13					</br>

## Java
Different versions of LineageOS require different JDK (Java Development Kit) versions.    </br>

LineageOS 18.1+: OpenJDK 11 (included in source download)                 </br>
LineageOS 16.0-17.1: OpenJDK 1.9 (included in source download)            </br>
LineageOS 14.1-15.1: OpenJDK 1.8 (install openjdk-8-jdk)                  </br>
LineageOS 11.0-13.0: OpenJDK 1.7 (install openjdk-7-jdk)*                 </br>

## 准备一些内核和设备文件
本来执行下面两条命令即可自动下载    </br>
source build/envsetup.sh          </br>
breakfast oneplus3                </br>
