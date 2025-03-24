# Industrial-Automation
PLC programming and Data analysis
#include <stdio.h>
void controlRobot(int position) {
    if (position < 100) {
        printf("Moving robot to position %d\n", position + 10);
    } else {
        printf("Target reached\n");
    }
}
int main() {
    controlRobot(50);
    return 0;
}
