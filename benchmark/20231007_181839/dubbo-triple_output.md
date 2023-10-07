# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.156 ops/ms
# Warmup Iteration   2: 4.824 ops/ms
# Warmup Iteration   3: 8.578 ops/ms
Iteration   1: 8.871 ops/ms
Iteration   2: 8.840 ops/ms
Iteration   3: 9.273 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.995 ±(99.9%) 4.407 ops/ms [Average]
  (min, avg, max) = (8.840, 8.995, 9.273), stdev = 0.242
  CI (99.9%): [4.588, 13.402] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:09
# Fork: 1 of 1
# Warmup Iteration   1: 2.905 ops/ms
# Warmup Iteration   2: 8.508 ops/ms
# Warmup Iteration   3: 9.328 ops/ms
Iteration   1: 9.235 ops/ms
Iteration   2: 9.605 ops/ms
Iteration   3: 9.283 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.374 ±(99.9%) 3.670 ops/ms [Average]
  (min, avg, max) = (9.235, 9.374, 9.605), stdev = 0.201
  CI (99.9%): [5.705, 13.044] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:02
# Fork: 1 of 1
# Warmup Iteration   1: 3.472 ops/ms
# Warmup Iteration   2: 8.535 ops/ms
# Warmup Iteration   3: 9.024 ops/ms
Iteration   1: 8.948 ops/ms
Iteration   2: 9.091 ops/ms
Iteration   3: 9.196 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.078 ±(99.9%) 2.273 ops/ms [Average]
  (min, avg, max) = (8.948, 9.078, 9.196), stdev = 0.125
  CI (99.9%): [6.805, 11.351] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.285 ops/ms
# Warmup Iteration   2: 7.210 ops/ms
# Warmup Iteration   3: 7.434 ops/ms
Iteration   1: 7.769 ops/ms
Iteration   2: 7.691 ops/ms
Iteration   3: 7.539 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.666 ±(99.9%) 2.133 ops/ms [Average]
  (min, avg, max) = (7.539, 7.666, 7.769), stdev = 0.117
  CI (99.9%): [5.533, 9.799] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:49
# Fork: 1 of 1
# Warmup Iteration   1: 10.930 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.864 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.593 ±(99.9%) 0.004 ms/op
Iteration   1: 3.605 ±(99.9%) 0.006 ms/op
Iteration   2: 3.522 ±(99.9%) 0.004 ms/op
Iteration   3: 3.427 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.518 ±(99.9%) 1.631 ms/op [Average]
  (min, avg, max) = (3.427, 3.518, 3.605), stdev = 0.089
  CI (99.9%): [1.887, 5.150] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:43
# Fork: 1 of 1
# Warmup Iteration   1: 8.434 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.646 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.418 ±(99.9%) 0.004 ms/op
Iteration   1: 3.386 ±(99.9%) 0.004 ms/op
Iteration   2: 3.346 ±(99.9%) 0.005 ms/op
Iteration   3: 3.421 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.384 ±(99.9%) 0.685 ms/op [Average]
  (min, avg, max) = (3.346, 3.384, 3.421), stdev = 0.038
  CI (99.9%): [2.700, 4.069] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:37
# Fork: 1 of 1
# Warmup Iteration   1: 10.315 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.918 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.602 ±(99.9%) 0.002 ms/op
Iteration   1: 3.574 ±(99.9%) 0.004 ms/op
Iteration   2: 3.465 ±(99.9%) 0.005 ms/op
Iteration   3: 3.454 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.498 ±(99.9%) 1.214 ms/op [Average]
  (min, avg, max) = (3.454, 3.498, 3.574), stdev = 0.067
  CI (99.9%): [2.284, 4.712] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 11.579 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 4.641 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.392 ±(99.9%) 0.006 ms/op
Iteration   1: 4.189 ±(99.9%) 0.007 ms/op
Iteration   2: 4.062 ±(99.9%) 0.008 ms/op
Iteration   3: 4.080 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.110 ±(99.9%) 1.257 ms/op [Average]
  (min, avg, max) = (4.062, 4.110, 4.189), stdev = 0.069
  CI (99.9%): [2.853, 5.367] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 9.708 ±(99.9%) 0.126 ms/op
# Warmup Iteration   2: 3.899 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.571 ±(99.9%) 0.012 ms/op
Iteration   1: 3.552 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.090 ms/op
                 createUser·p0.50:   3.379 ms/op
                 createUser·p0.90:   4.104 ms/op
                 createUser·p0.95:   4.538 ms/op
                 createUser·p0.99:   6.676 ms/op
                 createUser·p0.999:  17.924 ms/op
                 createUser·p0.9999: 20.380 ms/op
                 createUser·p1.00:   21.955 ms/op

Iteration   2: 3.613 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.896 ms/op
                 createUser·p0.50:   3.453 ms/op
                 createUser·p0.90:   4.162 ms/op
                 createUser·p0.95:   4.448 ms/op
                 createUser·p0.99:   6.832 ms/op
                 createUser·p0.999:  19.122 ms/op
                 createUser·p0.9999: 21.183 ms/op
                 createUser·p1.00:   24.674 ms/op

Iteration   3: 3.538 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.116 ms/op
                 createUser·p0.50:   3.367 ms/op
                 createUser·p0.90:   4.018 ms/op
                 createUser·p0.95:   4.383 ms/op
                 createUser·p0.99:   7.143 ms/op
                 createUser·p0.999:  19.744 ms/op
                 createUser·p0.9999: 25.087 ms/op
                 createUser·p1.00:   26.935 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 268910
  mean =      3.567 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5978 
    [ 2.500,  5.000) = 253582 
    [ 5.000,  7.500) = 7598 
    [ 7.500, 10.000) = 946 
    [10.000, 12.500) = 281 
    [12.500, 15.000) = 130 
    [15.000, 17.500) = 76 
    [17.500, 20.000) = 166 
    [20.000, 22.500) = 123 
    [22.500, 25.000) = 21 
    [25.000, 27.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      0.896 ms/op
     p(50.0000) =      3.391 ms/op
     p(90.0000) =      4.108 ms/op
     p(95.0000) =      4.448 ms/op
     p(99.0000) =      6.906 ms/op
     p(99.9000) =     18.645 ms/op
     p(99.9900) =     23.436 ms/op
     p(99.9990) =     26.636 ms/op
     p(99.9999) =     26.935 ms/op
    p(100.0000) =     26.935 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 8.056 ±(99.9%) 0.098 ms/op
# Warmup Iteration   2: 3.693 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.497 ±(99.9%) 0.011 ms/op
Iteration   1: 3.384 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.241 ms/op
                 existUser·p0.50:   3.265 ms/op
                 existUser·p0.90:   3.764 ms/op
                 existUser·p0.95:   4.167 ms/op
                 existUser·p0.99:   6.275 ms/op
                 existUser·p0.999:  11.043 ms/op
                 existUser·p0.9999: 21.430 ms/op
                 existUser·p1.00:   21.987 ms/op

Iteration   2: 3.446 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.460 ms/op
                 existUser·p0.50:   3.305 ms/op
                 existUser·p0.90:   3.908 ms/op
                 existUser·p0.95:   4.415 ms/op
                 existUser·p0.99:   6.488 ms/op
                 existUser·p0.999:  20.906 ms/op
                 existUser·p0.9999: 23.977 ms/op
                 existUser·p1.00:   25.002 ms/op

Iteration   3: 3.498 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.190 ms/op
                 existUser·p0.50:   3.314 ms/op
                 existUser·p0.90:   3.973 ms/op
                 existUser·p0.95:   4.522 ms/op
                 existUser·p0.99:   7.168 ms/op
                 existUser·p0.999:  18.285 ms/op
                 existUser·p0.9999: 27.356 ms/op
                 existUser·p1.00:   27.984 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 278895
  mean =      3.442 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7291 
    [ 2.500,  5.000) = 261844 
    [ 5.000,  7.500) = 8330 
    [ 7.500, 10.000) = 683 
    [10.000, 12.500) = 409 
    [12.500, 15.000) = 28 
    [15.000, 17.500) = 16 
    [17.500, 20.000) = 66 
    [20.000, 22.500) = 135 
    [22.500, 25.000) = 50 
    [25.000, 27.500) = 39 

  Percentiles, ms/op:
      p(0.0000) =      1.190 ms/op
     p(50.0000) =      3.289 ms/op
     p(90.0000) =      3.883 ms/op
     p(95.0000) =      4.350 ms/op
     p(99.0000) =      6.660 ms/op
     p(99.9000) =     18.517 ms/op
     p(99.9900) =     25.952 ms/op
     p(99.9990) =     27.853 ms/op
     p(99.9999) =     27.984 ms/op
    p(100.0000) =     27.984 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 9.365 ±(99.9%) 0.156 ms/op
# Warmup Iteration   2: 3.701 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.480 ±(99.9%) 0.010 ms/op
Iteration   1: 3.586 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   0.887 ms/op
                 getUser·p0.50:   3.371 ms/op
                 getUser·p0.90:   4.026 ms/op
                 getUser·p0.95:   4.530 ms/op
                 getUser·p0.99:   6.914 ms/op
                 getUser·p0.999:  24.106 ms/op
                 getUser·p0.9999: 36.962 ms/op
                 getUser·p1.00:   37.028 ms/op

Iteration   2: 3.522 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.423 ms/op
                 getUser·p0.50:   3.391 ms/op
                 getUser·p0.90:   3.858 ms/op
                 getUser·p0.95:   4.141 ms/op
                 getUser·p0.99:   6.873 ms/op
                 getUser·p0.999:  23.396 ms/op
                 getUser·p0.9999: 27.940 ms/op
                 getUser·p1.00:   28.312 ms/op

Iteration   3: 3.486 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.049 ms/op
                 getUser·p0.50:   3.375 ms/op
                 getUser·p0.90:   3.826 ms/op
                 getUser·p0.95:   4.052 ms/op
                 getUser·p0.99:   6.578 ms/op
                 getUser·p0.999:  19.794 ms/op
                 getUser·p0.9999: 30.091 ms/op
                 getUser·p1.00:   31.949 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 271730
  mean =      3.531 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4264 
    [ 2.500,  5.000) = 258908 
    [ 5.000,  7.500) = 6897 
    [ 7.500, 10.000) = 847 
    [10.000, 12.500) = 290 
    [12.500, 15.000) = 115 
    [15.000, 17.500) = 52 
    [17.500, 20.000) = 15 
    [20.000, 22.500) = 45 
    [22.500, 25.000) = 97 
    [25.000, 27.500) = 93 
    [27.500, 30.000) = 31 
    [30.000, 32.500) = 22 
    [32.500, 35.000) = 31 
    [35.000, 37.500) = 23 

  Percentiles, ms/op:
      p(0.0000) =      0.887 ms/op
     p(50.0000) =      3.379 ms/op
     p(90.0000) =      3.908 ms/op
     p(95.0000) =      4.235 ms/op
     p(99.0000) =      6.799 ms/op
     p(99.9000) =     23.217 ms/op
     p(99.9900) =     34.635 ms/op
     p(99.9990) =     36.962 ms/op
     p(99.9999) =     37.028 ms/op
    p(100.0000) =     37.028 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 10.758 ±(99.9%) 0.152 ms/op
# Warmup Iteration   2: 4.570 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.225 ±(99.9%) 0.015 ms/op
Iteration   1: 4.261 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.450 ms/op
                 listUser·p0.50:   4.022 ms/op
                 listUser·p0.90:   4.760 ms/op
                 listUser·p0.95:   5.423 ms/op
                 listUser·p0.99:   8.307 ms/op
                 listUser·p0.999:  22.315 ms/op
                 listUser·p0.9999: 26.542 ms/op
                 listUser·p1.00:   28.279 ms/op

Iteration   2: 4.169 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.552 ms/op
                 listUser·p0.50:   4.063 ms/op
                 listUser·p0.90:   4.571 ms/op
                 listUser·p0.95:   4.833 ms/op
                 listUser·p0.99:   7.849 ms/op
                 listUser·p0.999:  16.678 ms/op
                 listUser·p0.9999: 20.939 ms/op
                 listUser·p1.00:   21.037 ms/op

Iteration   3: 4.137 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.331 ms/op
                 listUser·p0.50:   3.928 ms/op
                 listUser·p0.90:   4.555 ms/op
                 listUser·p0.95:   4.907 ms/op
                 listUser·p0.99:   8.094 ms/op
                 listUser·p0.999:  16.744 ms/op
                 listUser·p0.9999: 28.288 ms/op
                 listUser·p1.00:   29.524 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 228959
  mean =      4.188 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 79 
    [ 2.500,  5.000) = 217351 
    [ 5.000,  7.500) = 8405 
    [ 7.500, 10.000) = 2022 
    [10.000, 12.500) = 287 
    [12.500, 15.000) = 320 
    [15.000, 17.500) = 261 
    [17.500, 20.000) = 61 
    [20.000, 22.500) = 89 
    [22.500, 25.000) = 52 
    [25.000, 27.500) = 19 

  Percentiles, ms/op:
      p(0.0000) =      1.331 ms/op
     p(50.0000) =      4.010 ms/op
     p(90.0000) =      4.620 ms/op
     p(95.0000) =      5.005 ms/op
     p(99.0000) =      8.069 ms/op
     p(99.9000) =     17.859 ms/op
     p(99.9900) =     25.629 ms/op
     p(99.9990) =     28.942 ms/op
     p(99.9999) =     29.524 ms/op
    p(100.0000) =     29.524 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.995 ± 4.407  ops/ms
ClientPb.existUser                       thrpt       3   9.374 ± 3.670  ops/ms
ClientPb.getUser                         thrpt       3   9.078 ± 2.273  ops/ms
ClientPb.listUser                        thrpt       3   7.666 ± 2.133  ops/ms
ClientPb.createUser                       avgt       3   3.518 ± 1.631   ms/op
ClientPb.existUser                        avgt       3   3.384 ± 0.685   ms/op
ClientPb.getUser                          avgt       3   3.498 ± 1.214   ms/op
ClientPb.listUser                         avgt       3   4.110 ± 1.257   ms/op
ClientPb.createUser                     sample  268910   3.567 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.896           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.391           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.108           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.448           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.906           ms/op
ClientPb.createUser:createUser·p0.999   sample          18.645           ms/op
ClientPb.createUser:createUser·p0.9999  sample          23.436           ms/op
ClientPb.createUser:createUser·p1.00    sample          26.935           ms/op
ClientPb.existUser                      sample  278895   3.442 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.190           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.289           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.883           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.350           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.660           ms/op
ClientPb.existUser:existUser·p0.999     sample          18.517           ms/op
ClientPb.existUser:existUser·p0.9999    sample          25.952           ms/op
ClientPb.existUser:existUser·p1.00      sample          27.984           ms/op
ClientPb.getUser                        sample  271730   3.531 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.887           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.379           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.908           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.235           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.799           ms/op
ClientPb.getUser:getUser·p0.999         sample          23.217           ms/op
ClientPb.getUser:getUser·p0.9999        sample          34.635           ms/op
ClientPb.getUser:getUser·p1.00          sample          37.028           ms/op
ClientPb.listUser                       sample  228959   4.188 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.331           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.010           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.620           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.005           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.069           ms/op
ClientPb.listUser:listUser·p0.999       sample          17.859           ms/op
ClientPb.listUser:listUser·p0.9999      sample          25.629           ms/op
ClientPb.listUser:listUser·p1.00        sample          29.524           ms/op
