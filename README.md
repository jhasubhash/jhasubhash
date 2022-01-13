### Hello World 👋
Summary of my life
```C++
#include <thread>
#include <life.h>
#include <work.h>

int main() {
    std::thread lifeThread(life::liveLife);
    std::thread workThread(work::doWork);
    // ...
    // do random stuff, just like this one
    // ...
    workThread.join();
    lifeThread.join();
    return 1;
}

```
> _"I am here to try out new ideas and collaborate on interesting ones. Feel free to contact me, if you have any interesting opportunnity aligning to my work and skill set"_ - Subhash Jha

