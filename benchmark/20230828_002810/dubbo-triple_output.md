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
# Warmup Iteration   1: 2.038 ops/ms
# Warmup Iteration   2: 4.842 ops/ms
# Warmup Iteration   3: 7.935 ops/ms
Iteration   1: 8.843 ops/ms
Iteration   2: 8.938 ops/ms
Iteration   3: 9.124 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.968 ±(99.9%) 2.602 ops/ms [Average]
  (min, avg, max) = (8.843, 8.968, 9.124), stdev = 0.143
  CI (99.9%): [6.366, 11.570] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 2.994 ops/ms
# Warmup Iteration   2: 8.499 ops/ms
# Warmup Iteration   3: 9.293 ops/ms
Iteration   1: 9.013 ops/ms
Iteration   2: 9.328 ops/ms
Iteration   3: 9.380 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.240 ±(99.9%) 3.623 ops/ms [Average]
  (min, avg, max) = (9.013, 9.240, 9.380), stdev = 0.199
  CI (99.9%): [5.618, 12.863] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 2.877 ops/ms
# Warmup Iteration   2: 8.226 ops/ms
# Warmup Iteration   3: 8.935 ops/ms
Iteration   1: 8.888 ops/ms
Iteration   2: 9.114 ops/ms
Iteration   3: 8.997 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.000 ±(99.9%) 2.057 ops/ms [Average]
  (min, avg, max) = (8.888, 9.000, 9.114), stdev = 0.113
  CI (99.9%): [6.942, 11.057] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 2.662 ops/ms
# Warmup Iteration   2: 7.152 ops/ms
# Warmup Iteration   3: 7.611 ops/ms
Iteration   1: 7.688 ops/ms
Iteration   2: 7.976 ops/ms
Iteration   3: 8.080 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.914 ±(99.9%) 3.704 ops/ms [Average]
  (min, avg, max) = (7.688, 7.914, 8.080), stdev = 0.203
  CI (99.9%): [4.210, 11.619] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 12.054 ±(99.9%) 0.062 ms/op
# Warmup Iteration   2: 3.864 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.696 ±(99.9%) 0.010 ms/op
Iteration   1: 3.578 ±(99.9%) 0.008 ms/op
Iteration   2: 3.659 ±(99.9%) 0.006 ms/op
Iteration   3: 3.454 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.564 ±(99.9%) 1.888 ms/op [Average]
  (min, avg, max) = (3.454, 3.564, 3.659), stdev = 0.103
  CI (99.9%): [1.676, 5.451] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 8.780 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.675 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.437 ±(99.9%) 0.006 ms/op
Iteration   1: 3.376 ±(99.9%) 0.005 ms/op
Iteration   2: 3.338 ±(99.9%) 0.006 ms/op
Iteration   3: 3.362 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.359 ±(99.9%) 0.343 ms/op [Average]
  (min, avg, max) = (3.338, 3.359, 3.376), stdev = 0.019
  CI (99.9%): [3.016, 3.702] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 9.664 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.853 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.756 ±(99.9%) 0.005 ms/op
Iteration   1: 3.659 ±(99.9%) 0.007 ms/op
Iteration   2: 3.730 ±(99.9%) 0.006 ms/op
Iteration   3: 3.665 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.685 ±(99.9%) 0.719 ms/op [Average]
  (min, avg, max) = (3.659, 3.685, 3.730), stdev = 0.039
  CI (99.9%): [2.966, 4.403] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 10.978 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 4.511 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.127 ±(99.9%) 0.008 ms/op
Iteration   1: 4.141 ±(99.9%) 0.012 ms/op
Iteration   2: 4.092 ±(99.9%) 0.010 ms/op
Iteration   3: 4.008 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.080 ±(99.9%) 1.227 ms/op [Average]
  (min, avg, max) = (4.008, 4.080, 4.141), stdev = 0.067
  CI (99.9%): [2.854, 5.307] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 10.647 ±(99.9%) 0.149 ms/op
# Warmup Iteration   2: 4.182 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.855 ±(99.9%) 0.016 ms/op
Iteration   1: 3.598 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.720 ms/op
                 createUser·p0.50:   3.432 ms/op
                 createUser·p0.90:   4.104 ms/op
                 createUser·p0.95:   4.514 ms/op
                 createUser·p0.99:   6.832 ms/op
                 createUser·p0.999:  21.072 ms/op
                 createUser·p0.9999: 24.248 ms/op
                 createUser·p1.00:   26.935 ms/op

Iteration   2: 3.799 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.307 ms/op
                 createUser·p0.50:   3.592 ms/op
                 createUser·p0.90:   4.702 ms/op
                 createUser·p0.95:   4.973 ms/op
                 createUser·p0.99:   6.611 ms/op
                 createUser·p0.999:  23.200 ms/op
                 createUser·p0.9999: 26.069 ms/op
                 createUser·p1.00:   28.672 ms/op

Iteration   3: 3.574 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.000 ms/op
                 createUser·p0.50:   3.351 ms/op
                 createUser·p0.90:   4.121 ms/op
                 createUser·p0.95:   4.727 ms/op
                 createUser·p0.99:   7.111 ms/op
                 createUser·p0.999:  22.366 ms/op
                 createUser·p0.9999: 27.701 ms/op
                 createUser·p1.00:   29.950 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 262734
  mean =      3.654 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2766 
    [ 2.500,  5.000) = 249490 
    [ 5.000,  7.500) = 8544 
    [ 7.500, 10.000) = 1410 
    [10.000, 12.500) = 193 
    [12.500, 15.000) = 11 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 7 
    [20.000, 22.500) = 78 
    [22.500, 25.000) = 141 
    [25.000, 27.500) = 80 

  Percentiles, ms/op:
      p(0.0000) =      1.000 ms/op
     p(50.0000) =      3.465 ms/op
     p(90.0000) =      4.309 ms/op
     p(95.0000) =      4.852 ms/op
     p(99.0000) =      6.873 ms/op
     p(99.9000) =     22.086 ms/op
     p(99.9900) =     27.221 ms/op
     p(99.9990) =     28.738 ms/op
     p(99.9999) =     29.950 ms/op
    p(100.0000) =     29.950 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 9.497 ±(99.9%) 0.139 ms/op
# Warmup Iteration   2: 3.712 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.502 ±(99.9%) 0.011 ms/op
Iteration   1: 3.319 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.339 ms/op
                 existUser·p0.50:   3.207 ms/op
                 existUser·p0.90:   3.600 ms/op
                 existUser·p0.95:   4.145 ms/op
                 existUser·p0.99:   6.316 ms/op
                 existUser·p0.999:  16.720 ms/op
                 existUser·p0.9999: 23.593 ms/op
                 existUser·p1.00:   24.052 ms/op

Iteration   2: 3.339 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.614 ms/op
                 existUser·p0.50:   3.195 ms/op
                 existUser·p0.90:   3.617 ms/op
                 existUser·p0.95:   3.985 ms/op
                 existUser·p0.99:   6.997 ms/op
                 existUser·p0.999:  12.734 ms/op
                 existUser·p0.9999: 22.736 ms/op
                 existUser·p1.00:   24.019 ms/op

Iteration   3: 3.315 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.147 ms/op
                 existUser·p0.50:   3.285 ms/op
                 existUser·p0.90:   3.482 ms/op
                 existUser·p0.95:   3.789 ms/op
                 existUser·p0.99:   5.980 ms/op
                 existUser·p0.999:  17.742 ms/op
                 existUser·p0.9999: 30.125 ms/op
                 existUser·p1.00:   30.540 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 288646
  mean =      3.324 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12426 
    [ 2.500,  5.000) = 269893 
    [ 5.000,  7.500) = 4623 
    [ 7.500, 10.000) = 1095 
    [10.000, 12.500) = 309 
    [12.500, 15.000) = 44 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 20 
    [20.000, 22.500) = 97 
    [22.500, 25.000) = 85 
    [25.000, 27.500) = 22 
    [27.500, 30.000) = 18 
    [30.000, 32.500) = 14 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.147 ms/op
     p(50.0000) =      3.236 ms/op
     p(90.0000) =      3.572 ms/op
     p(95.0000) =      3.928 ms/op
     p(99.0000) =      6.398 ms/op
     p(99.9000) =     12.960 ms/op
     p(99.9900) =     29.435 ms/op
     p(99.9990) =     30.343 ms/op
     p(99.9999) =     30.540 ms/op
    p(100.0000) =     30.540 ms/op


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
# Warmup Iteration   1: 9.857 ±(99.9%) 0.141 ms/op
# Warmup Iteration   2: 3.884 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.632 ±(99.9%) 0.012 ms/op
Iteration   1: 3.463 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.389 ms/op
                 getUser·p0.50:   3.351 ms/op
                 getUser·p0.90:   3.760 ms/op
                 getUser·p0.95:   3.944 ms/op
                 getUser·p0.99:   6.644 ms/op
                 getUser·p0.999:  19.606 ms/op
                 getUser·p0.9999: 23.718 ms/op
                 getUser·p1.00:   24.773 ms/op

Iteration   2: 3.512 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.288 ms/op
                 getUser·p0.50:   3.391 ms/op
                 getUser·p0.90:   3.883 ms/op
                 getUser·p0.95:   4.243 ms/op
                 getUser·p0.99:   6.660 ms/op
                 getUser·p0.999:  22.048 ms/op
                 getUser·p0.9999: 29.426 ms/op
                 getUser·p1.00:   29.917 ms/op

Iteration   3: 3.560 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.935 ms/op
                 getUser·p0.50:   3.351 ms/op
                 getUser·p0.90:   4.202 ms/op
                 getUser·p0.95:   4.626 ms/op
                 getUser·p0.99:   7.069 ms/op
                 getUser·p0.999:  19.107 ms/op
                 getUser·p0.9999: 36.832 ms/op
                 getUser·p1.00:   37.224 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 273405
  mean =      3.511 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3182 
    [ 2.500,  5.000) = 262142 
    [ 5.000,  7.500) = 6263 
    [ 7.500, 10.000) = 1272 
    [10.000, 12.500) = 236 
    [12.500, 15.000) = 22 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 26 
    [20.000, 22.500) = 73 
    [22.500, 25.000) = 112 
    [25.000, 27.500) = 14 
    [27.500, 30.000) = 31 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 13 
    [35.000, 37.500) = 19 

  Percentiles, ms/op:
      p(0.0000) =      1.288 ms/op
     p(50.0000) =      3.367 ms/op
     p(90.0000) =      3.899 ms/op
     p(95.0000) =      4.342 ms/op
     p(99.0000) =      6.774 ms/op
     p(99.9000) =     19.333 ms/op
     p(99.9900) =     34.450 ms/op
     p(99.9990) =     37.128 ms/op
     p(99.9999) =     37.224 ms/op
    p(100.0000) =     37.224 ms/op


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
# Warmup Iteration   1: 12.070 ±(99.9%) 0.174 ms/op
# Warmup Iteration   2: 4.674 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.209 ±(99.9%) 0.014 ms/op
Iteration   1: 4.430 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.614 ms/op
                 listUser·p0.50:   4.153 ms/op
                 listUser·p0.90:   5.399 ms/op
                 listUser·p0.95:   6.406 ms/op
                 listUser·p0.99:   8.387 ms/op
                 listUser·p0.999:  22.043 ms/op
                 listUser·p0.9999: 25.846 ms/op
                 listUser·p1.00:   27.066 ms/op

Iteration   2: 4.244 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.937 ms/op
                 listUser·p0.50:   3.998 ms/op
                 listUser·p0.90:   4.710 ms/op
                 listUser·p0.95:   6.078 ms/op
                 listUser·p0.99:   8.995 ms/op
                 listUser·p0.999:  16.781 ms/op
                 listUser·p0.9999: 21.037 ms/op
                 listUser·p1.00:   22.348 ms/op

Iteration   3: 4.092 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.277 ms/op
                 listUser·p0.50:   3.990 ms/op
                 listUser·p0.90:   4.473 ms/op
                 listUser·p0.95:   4.841 ms/op
                 listUser·p0.99:   7.780 ms/op
                 listUser·p0.999:  15.729 ms/op
                 listUser·p0.9999: 19.661 ms/op
                 listUser·p1.00:   19.792 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 225783
  mean =      4.251 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21 
    [ 2.500,  5.000) = 208804 
    [ 5.000,  7.500) = 13148 
    [ 7.500, 10.000) = 2611 
    [10.000, 12.500) = 595 
    [12.500, 15.000) = 156 
    [15.000, 17.500) = 198 
    [17.500, 20.000) = 102 
    [20.000, 22.500) = 86 
    [22.500, 25.000) = 34 
    [25.000, 27.500) = 28 

  Percentiles, ms/op:
      p(0.0000) =      1.614 ms/op
     p(50.0000) =      4.018 ms/op
     p(90.0000) =      4.768 ms/op
     p(95.0000) =      6.062 ms/op
     p(99.0000) =      8.454 ms/op
     p(99.9000) =     18.521 ms/op
     p(99.9900) =     25.306 ms/op
     p(99.9990) =     26.384 ms/op
     p(99.9999) =     27.066 ms/op
    p(100.0000) =     27.066 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.968 ± 2.602  ops/ms
ClientPb.existUser                       thrpt       3   9.240 ± 3.623  ops/ms
ClientPb.getUser                         thrpt       3   9.000 ± 2.057  ops/ms
ClientPb.listUser                        thrpt       3   7.914 ± 3.704  ops/ms
ClientPb.createUser                       avgt       3   3.564 ± 1.888   ms/op
ClientPb.existUser                        avgt       3   3.359 ± 0.343   ms/op
ClientPb.getUser                          avgt       3   3.685 ± 0.719   ms/op
ClientPb.listUser                         avgt       3   4.080 ± 1.227   ms/op
ClientPb.createUser                     sample  262734   3.654 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.000           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.465           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.309           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.852           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.873           ms/op
ClientPb.createUser:createUser·p0.999   sample          22.086           ms/op
ClientPb.createUser:createUser·p0.9999  sample          27.221           ms/op
ClientPb.createUser:createUser·p1.00    sample          29.950           ms/op
ClientPb.existUser                      sample  288646   3.324 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.147           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.236           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.572           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.928           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.398           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.960           ms/op
ClientPb.existUser:existUser·p0.9999    sample          29.435           ms/op
ClientPb.existUser:existUser·p1.00      sample          30.540           ms/op
ClientPb.getUser                        sample  273405   3.511 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.288           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.367           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.899           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.342           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.774           ms/op
ClientPb.getUser:getUser·p0.999         sample          19.333           ms/op
ClientPb.getUser:getUser·p0.9999        sample          34.450           ms/op
ClientPb.getUser:getUser·p1.00          sample          37.224           ms/op
ClientPb.listUser                       sample  225783   4.251 ± 0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.614           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.018           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.768           ms/op
ClientPb.listUser:listUser·p0.95        sample           6.062           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.454           ms/op
ClientPb.listUser:listUser·p0.999       sample          18.521           ms/op
ClientPb.listUser:listUser·p0.9999      sample          25.306           ms/op
ClientPb.listUser:listUser·p1.00        sample          27.066           ms/op
