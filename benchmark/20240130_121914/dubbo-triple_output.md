# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.752 ops/ms
# Warmup Iteration   2: 11.948 ops/ms
# Warmup Iteration   3: 12.326 ops/ms
Iteration   1: 12.609 ops/ms
Iteration   2: 12.573 ops/ms
Iteration   3: 12.523 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.568 ±(99.9%) 0.785 ops/ms [Average]
  (min, avg, max) = (12.523, 12.568, 12.609), stdev = 0.043
  CI (99.9%): [11.784, 13.353] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.628 ops/ms
# Warmup Iteration   2: 12.827 ops/ms
# Warmup Iteration   3: 12.980 ops/ms
Iteration   1: 12.785 ops/ms
Iteration   2: 12.951 ops/ms
Iteration   3: 12.676 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.804 ±(99.9%) 2.523 ops/ms [Average]
  (min, avg, max) = (12.676, 12.804, 12.951), stdev = 0.138
  CI (99.9%): [10.280, 15.327] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:47
# Fork: 1 of 1
# Warmup Iteration   1: 7.639 ops/ms
# Warmup Iteration   2: 12.444 ops/ms
# Warmup Iteration   3: 12.744 ops/ms
Iteration   1: 12.814 ops/ms
Iteration   2: 12.733 ops/ms
Iteration   3: 12.695 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.747 ±(99.9%) 1.108 ops/ms [Average]
  (min, avg, max) = (12.695, 12.747, 12.814), stdev = 0.061
  CI (99.9%): [11.640, 13.855] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.621 ops/ms
# Warmup Iteration   2: 10.530 ops/ms
# Warmup Iteration   3: 10.656 ops/ms
Iteration   1: 10.611 ops/ms
Iteration   2: 10.619 ops/ms
Iteration   3: 10.627 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.619 ±(99.9%) 0.142 ops/ms [Average]
  (min, avg, max) = (10.611, 10.619, 10.627), stdev = 0.008
  CI (99.9%): [10.476, 10.761] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:38
# Fork: 1 of 1
# Warmup Iteration   1: 4.107 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.611 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.530 ±(99.9%) 0.004 ms/op
Iteration   1: 2.555 ±(99.9%) 0.004 ms/op
Iteration   2: 2.580 ±(99.9%) 0.004 ms/op
Iteration   3: 2.570 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.569 ±(99.9%) 0.226 ms/op [Average]
  (min, avg, max) = (2.555, 2.569, 2.580), stdev = 0.012
  CI (99.9%): [2.343, 2.794] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:33
# Fork: 1 of 1
# Warmup Iteration   1: 3.811 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.483 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.492 ±(99.9%) 0.004 ms/op
Iteration   1: 2.457 ±(99.9%) 0.004 ms/op
Iteration   2: 2.492 ±(99.9%) 0.004 ms/op
Iteration   3: 2.468 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.472 ±(99.9%) 0.325 ms/op [Average]
  (min, avg, max) = (2.457, 2.472, 2.492), stdev = 0.018
  CI (99.9%): [2.147, 2.798] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:28
# Fork: 1 of 1
# Warmup Iteration   1: 4.417 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.665 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.565 ±(99.9%) 0.005 ms/op
Iteration   1: 2.568 ±(99.9%) 0.005 ms/op
Iteration   2: 2.551 ±(99.9%) 0.004 ms/op
Iteration   3: 2.554 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.558 ±(99.9%) 0.166 ms/op [Average]
  (min, avg, max) = (2.551, 2.558, 2.568), stdev = 0.009
  CI (99.9%): [2.392, 2.724] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:23
# Fork: 1 of 1
# Warmup Iteration   1: 4.754 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.111 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.080 ±(99.9%) 0.006 ms/op
Iteration   1: 3.060 ±(99.9%) 0.006 ms/op
Iteration   2: 3.087 ±(99.9%) 0.005 ms/op
Iteration   3: 3.090 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.079 ±(99.9%) 0.305 ms/op [Average]
  (min, avg, max) = (3.060, 3.079, 3.090), stdev = 0.017
  CI (99.9%): [2.774, 3.384] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:18
# Fork: 1 of 1
# Warmup Iteration   1: 4.360 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 2.715 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.581 ±(99.9%) 0.006 ms/op
Iteration   1: 2.567 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.959 ms/op
                 createUser·p0.50:   2.593 ms/op
                 createUser·p0.90:   3.125 ms/op
                 createUser·p0.95:   3.285 ms/op
                 createUser·p0.99:   4.035 ms/op
                 createUser·p0.999:  11.842 ms/op
                 createUser·p0.9999: 14.126 ms/op
                 createUser·p1.00:   14.959 ms/op

Iteration   2: 2.548 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.961 ms/op
                 createUser·p0.50:   2.597 ms/op
                 createUser·p0.90:   3.101 ms/op
                 createUser·p0.95:   3.224 ms/op
                 createUser·p0.99:   3.777 ms/op
                 createUser·p0.999:  9.380 ms/op
                 createUser·p0.9999: 13.661 ms/op
                 createUser·p1.00:   14.926 ms/op

Iteration   3: 2.534 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.057 ms/op
                 createUser·p0.50:   2.621 ms/op
                 createUser·p0.90:   3.080 ms/op
                 createUser·p0.95:   3.187 ms/op
                 createUser·p0.99:   3.674 ms/op
                 createUser·p0.999:  8.946 ms/op
                 createUser·p0.9999: 11.754 ms/op
                 createUser·p1.00:   12.403 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 376199
  mean =      2.549 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 23 
    [ 1.250,  2.500) = 179550 
    [ 2.500,  3.750) = 192243 
    [ 3.750,  5.000) = 3590 
    [ 5.000,  6.250) = 386 
    [ 6.250,  7.500) = 22 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 72 
    [10.000, 11.250) = 92 
    [11.250, 12.500) = 89 
    [12.500, 13.750) = 89 
    [13.750, 15.000) = 42 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.959 ms/op
     p(50.0000) =      2.605 ms/op
     p(90.0000) =      3.101 ms/op
     p(95.0000) =      3.232 ms/op
     p(99.0000) =      3.834 ms/op
     p(99.9000) =      9.024 ms/op
     p(99.9900) =     13.834 ms/op
     p(99.9990) =     14.863 ms/op
     p(99.9999) =     14.959 ms/op
    p(100.0000) =     14.959 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.747 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.508 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.484 ±(99.9%) 0.005 ms/op
Iteration   1: 2.462 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.916 ms/op
                 existUser·p0.50:   2.552 ms/op
                 existUser·p0.90:   2.994 ms/op
                 existUser·p0.95:   3.097 ms/op
                 existUser·p0.99:   3.547 ms/op
                 existUser·p0.999:  5.249 ms/op
                 existUser·p0.9999: 13.631 ms/op
                 existUser·p1.00:   13.943 ms/op

Iteration   2: 2.489 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.555 ms/op
                 existUser·p0.50:   2.494 ms/op
                 existUser·p0.90:   3.052 ms/op
                 existUser·p0.95:   3.187 ms/op
                 existUser·p0.99:   3.686 ms/op
                 existUser·p0.999:  8.114 ms/op
                 existUser·p0.9999: 13.418 ms/op
                 existUser·p1.00:   13.779 ms/op

Iteration   3: 2.479 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.992 ms/op
                 existUser·p0.50:   2.572 ms/op
                 existUser·p0.90:   3.011 ms/op
                 existUser·p0.95:   3.117 ms/op
                 existUser·p0.99:   3.695 ms/op
                 existUser·p0.999:  8.444 ms/op
                 existUser·p0.9999: 11.651 ms/op
                 existUser·p1.00:   12.026 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 387174
  mean =      2.477 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 45 
    [ 1.250,  2.500) = 190829 
    [ 2.500,  3.750) = 193098 
    [ 3.750,  5.000) = 2467 
    [ 5.000,  6.250) = 331 
    [ 6.250,  7.500) = 49 
    [ 7.500,  8.750) = 8 
    [ 8.750, 10.000) = 73 
    [10.000, 11.250) = 57 
    [11.250, 12.500) = 69 
    [12.500, 13.750) = 142 
    [13.750, 15.000) = 6 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.555 ms/op
     p(50.0000) =      2.540 ms/op
     p(90.0000) =      3.019 ms/op
     p(95.0000) =      3.133 ms/op
     p(99.0000) =      3.645 ms/op
     p(99.9000) =      6.562 ms/op
     p(99.9900) =     13.472 ms/op
     p(99.9990) =     13.794 ms/op
     p(99.9999) =     13.943 ms/op
    p(100.0000) =     13.943 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:09
# Fork: 1 of 1
# Warmup Iteration   1: 4.128 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 2.646 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.560 ±(99.9%) 0.006 ms/op
Iteration   1: 2.521 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.964 ms/op
                 getUser·p0.50:   2.519 ms/op
                 getUser·p0.90:   3.080 ms/op
                 getUser·p0.95:   3.228 ms/op
                 getUser·p0.99:   3.973 ms/op
                 getUser·p0.999:  12.026 ms/op
                 getUser·p0.9999: 13.550 ms/op
                 getUser·p1.00:   14.287 ms/op

Iteration   2: 2.519 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.844 ms/op
                 getUser·p0.50:   2.535 ms/op
                 getUser·p0.90:   3.068 ms/op
                 getUser·p0.95:   3.199 ms/op
                 getUser·p0.99:   3.858 ms/op
                 getUser·p0.999:  9.672 ms/op
                 getUser·p0.9999: 14.451 ms/op
                 getUser·p1.00:   17.531 ms/op

Iteration   3: 2.547 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.608 ms/op
                 getUser·p0.50:   2.572 ms/op
                 getUser·p0.90:   3.121 ms/op
                 getUser·p0.95:   3.265 ms/op
                 getUser·p0.99:   3.879 ms/op
                 getUser·p0.999:  5.648 ms/op
                 getUser·p0.9999: 10.617 ms/op
                 getUser·p1.00:   11.370 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 379253
  mean =      2.529 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 71 
    [ 1.250,  2.500) = 185641 
    [ 2.500,  3.750) = 188546 
    [ 3.750,  5.000) = 4143 
    [ 5.000,  6.250) = 445 
    [ 6.250,  7.500) = 35 
    [ 7.500,  8.750) = 22 
    [ 8.750, 10.000) = 77 
    [10.000, 11.250) = 51 
    [11.250, 12.500) = 78 
    [12.500, 13.750) = 93 
    [13.750, 15.000) = 46 
    [15.000, 16.250) = 4 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.608 ms/op
     p(50.0000) =      2.540 ms/op
     p(90.0000) =      3.088 ms/op
     p(95.0000) =      3.232 ms/op
     p(99.0000) =      3.899 ms/op
     p(99.9000) =      7.344 ms/op
     p(99.9900) =     14.090 ms/op
     p(99.9990) =     15.254 ms/op
     p(99.9999) =     17.531 ms/op
    p(100.0000) =     17.531 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.922 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 3.102 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.096 ±(99.9%) 0.009 ms/op
Iteration   1: 3.069 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.973 ms/op
                 listUser·p0.50:   3.011 ms/op
                 listUser·p0.90:   3.957 ms/op
                 listUser·p0.95:   4.465 ms/op
                 listUser·p0.99:   5.792 ms/op
                 listUser·p0.999:  9.798 ms/op
                 listUser·p0.9999: 11.282 ms/op
                 listUser·p1.00:   11.960 ms/op

Iteration   2: 3.085 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.818 ms/op
                 listUser·p0.50:   3.019 ms/op
                 listUser·p0.90:   3.994 ms/op
                 listUser·p0.95:   4.522 ms/op
                 listUser·p0.99:   5.808 ms/op
                 listUser·p0.999:  9.735 ms/op
                 listUser·p0.9999: 11.914 ms/op
                 listUser·p1.00:   13.648 ms/op

Iteration   3: 3.056 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.972 ms/op
                 listUser·p0.50:   2.998 ms/op
                 listUser·p0.90:   3.908 ms/op
                 listUser·p0.95:   4.383 ms/op
                 listUser·p0.99:   5.480 ms/op
                 listUser·p0.999:  9.827 ms/op
                 listUser·p0.9999: 11.339 ms/op
                 listUser·p1.00:   11.731 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 312371
  mean =      3.070 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 64 
    [ 1.250,  2.500) = 81575 
    [ 2.500,  3.750) = 187800 
    [ 3.750,  5.000) = 34985 
    [ 5.000,  6.250) = 6460 
    [ 6.250,  7.500) = 819 
    [ 7.500,  8.750) = 159 
    [ 8.750, 10.000) = 241 
    [10.000, 11.250) = 217 
    [11.250, 12.500) = 45 
    [12.500, 13.750) = 6 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.818 ms/op
     p(50.0000) =      3.006 ms/op
     p(90.0000) =      3.953 ms/op
     p(95.0000) =      4.465 ms/op
     p(99.0000) =      5.702 ms/op
     p(99.9000) =      9.785 ms/op
     p(99.9900) =     11.580 ms/op
     p(99.9990) =     13.319 ms/op
     p(99.9999) =     13.648 ms/op
    p(100.0000) =     13.648 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.568 ± 0.785  ops/ms
ClientPb.existUser                       thrpt       3  12.804 ± 2.523  ops/ms
ClientPb.getUser                         thrpt       3  12.747 ± 1.108  ops/ms
ClientPb.listUser                        thrpt       3  10.619 ± 0.142  ops/ms
ClientPb.createUser                       avgt       3   2.569 ± 0.226   ms/op
ClientPb.existUser                        avgt       3   2.472 ± 0.325   ms/op
ClientPb.getUser                          avgt       3   2.558 ± 0.166   ms/op
ClientPb.listUser                         avgt       3   3.079 ± 0.305   ms/op
ClientPb.createUser                     sample  376199   2.549 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.959           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.605           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.101           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.232           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.834           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.024           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.834           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.959           ms/op
ClientPb.existUser                      sample  387174   2.477 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.555           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.540           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.019           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.133           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.645           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.562           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.472           ms/op
ClientPb.existUser:existUser·p1.00      sample          13.943           ms/op
ClientPb.getUser                        sample  379253   2.529 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.608           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.540           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.088           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.232           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.899           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.344           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.090           ms/op
ClientPb.getUser:getUser·p1.00          sample          17.531           ms/op
ClientPb.listUser                       sample  312371   3.070 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.818           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.006           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.953           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.465           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.702           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.785           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.580           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.648           ms/op
