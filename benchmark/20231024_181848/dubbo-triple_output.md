# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.343 ops/ms
# Warmup Iteration   2: 5.561 ops/ms
# Warmup Iteration   3: 8.946 ops/ms
Iteration   1: 9.415 ops/ms
Iteration   2: 9.693 ops/ms
Iteration   3: 9.856 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.655 ±(99.9%) 4.064 ops/ms [Average]
  (min, avg, max) = (9.415, 9.655, 9.856), stdev = 0.223
  CI (99.9%): [5.591, 13.719] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 3.192 ops/ms
# Warmup Iteration   2: 9.090 ops/ms
# Warmup Iteration   3: 10.223 ops/ms
Iteration   1: 10.014 ops/ms
Iteration   2: 10.386 ops/ms
Iteration   3: 10.155 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.185 ±(99.9%) 3.419 ops/ms [Average]
  (min, avg, max) = (10.014, 10.185, 10.386), stdev = 0.187
  CI (99.9%): [6.766, 13.604] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 3.480 ops/ms
# Warmup Iteration   2: 8.934 ops/ms
# Warmup Iteration   3: 9.925 ops/ms
Iteration   1: 9.512 ops/ms
Iteration   2: 9.882 ops/ms
Iteration   3: 9.935 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.777 ±(99.9%) 4.203 ops/ms [Average]
  (min, avg, max) = (9.512, 9.777, 9.935), stdev = 0.230
  CI (99.9%): [5.574, 13.979] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 3.381 ops/ms
# Warmup Iteration   2: 7.832 ops/ms
# Warmup Iteration   3: 8.163 ops/ms
Iteration   1: 8.387 ops/ms
Iteration   2: 8.340 ops/ms
Iteration   3: 8.082 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.269 ±(99.9%) 2.998 ops/ms [Average]
  (min, avg, max) = (8.082, 8.269, 8.387), stdev = 0.164
  CI (99.9%): [5.272, 11.267] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 9.027 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.509 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.474 ±(99.9%) 0.002 ms/op
Iteration   1: 3.319 ±(99.9%) 0.003 ms/op
Iteration   2: 3.160 ±(99.9%) 0.004 ms/op
Iteration   3: 3.285 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.255 ±(99.9%) 1.529 ms/op [Average]
  (min, avg, max) = (3.160, 3.255, 3.319), stdev = 0.084
  CI (99.9%): [1.726, 4.784] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 7.878 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.355 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.205 ±(99.9%) 0.002 ms/op
Iteration   1: 3.108 ±(99.9%) 0.003 ms/op
Iteration   2: 3.137 ±(99.9%) 0.004 ms/op
Iteration   3: 3.227 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.157 ±(99.9%) 1.125 ms/op [Average]
  (min, avg, max) = (3.108, 3.157, 3.227), stdev = 0.062
  CI (99.9%): [2.033, 4.282] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 7.959 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.474 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.270 ±(99.9%) 0.003 ms/op
Iteration   1: 3.266 ±(99.9%) 0.003 ms/op
Iteration   2: 3.150 ±(99.9%) 0.003 ms/op
Iteration   3: 3.240 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.219 ±(99.9%) 1.108 ms/op [Average]
  (min, avg, max) = (3.150, 3.219, 3.266), stdev = 0.061
  CI (99.9%): [2.110, 4.327] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 10.639 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 4.179 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.901 ±(99.9%) 0.003 ms/op
Iteration   1: 3.832 ±(99.9%) 0.006 ms/op
Iteration   2: 3.829 ±(99.9%) 0.006 ms/op
Iteration   3: 3.857 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.839 ±(99.9%) 0.278 ms/op [Average]
  (min, avg, max) = (3.829, 3.839, 3.857), stdev = 0.015
  CI (99.9%): [3.561, 4.117] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 9.527 ±(99.9%) 0.099 ms/op
# Warmup Iteration   2: 3.989 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.380 ±(99.9%) 0.010 ms/op
Iteration   1: 3.329 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.481 ms/op
                 createUser·p0.50:   3.224 ms/op
                 createUser·p0.90:   3.813 ms/op
                 createUser·p0.95:   4.088 ms/op
                 createUser·p0.99:   5.997 ms/op
                 createUser·p0.999:  16.653 ms/op
                 createUser·p0.9999: 21.140 ms/op
                 createUser·p1.00:   22.053 ms/op

Iteration   2: 3.265 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.055 ms/op
                 createUser·p0.50:   3.260 ms/op
                 createUser·p0.90:   3.564 ms/op
                 createUser·p0.95:   3.822 ms/op
                 createUser·p0.99:   5.194 ms/op
                 createUser·p0.999:  17.642 ms/op
                 createUser·p0.9999: 28.266 ms/op
                 createUser·p1.00:   29.557 ms/op

Iteration   3: 3.346 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.949 ms/op
                 createUser·p0.50:   3.293 ms/op
                 createUser·p0.90:   3.777 ms/op
                 createUser·p0.95:   4.014 ms/op
                 createUser·p0.99:   4.882 ms/op
                 createUser·p0.999:  17.021 ms/op
                 createUser·p0.9999: 25.395 ms/op
                 createUser·p1.00:   26.411 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 289557
  mean =      3.313 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14970 
    [ 2.500,  5.000) = 270859 
    [ 5.000,  7.500) = 2803 
    [ 7.500, 10.000) = 338 
    [10.000, 12.500) = 201 
    [12.500, 15.000) = 41 
    [15.000, 17.500) = 68 
    [17.500, 20.000) = 62 
    [20.000, 22.500) = 81 
    [22.500, 25.000) = 71 
    [25.000, 27.500) = 45 

  Percentiles, ms/op:
      p(0.0000) =      0.949 ms/op
     p(50.0000) =      3.265 ms/op
     p(90.0000) =      3.736 ms/op
     p(95.0000) =      3.985 ms/op
     p(99.0000) =      5.374 ms/op
     p(99.9000) =     17.170 ms/op
     p(99.9900) =     26.971 ms/op
     p(99.9990) =     29.112 ms/op
     p(99.9999) =     29.557 ms/op
    p(100.0000) =     29.557 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 7.538 ±(99.9%) 0.106 ms/op
# Warmup Iteration   2: 3.354 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.144 ±(99.9%) 0.007 ms/op
Iteration   1: 3.227 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.278 ms/op
                 existUser·p0.50:   3.195 ms/op
                 existUser·p0.90:   3.514 ms/op
                 existUser·p0.95:   3.760 ms/op
                 existUser·p0.99:   5.603 ms/op
                 existUser·p0.999:  15.116 ms/op
                 existUser·p0.9999: 21.153 ms/op
                 existUser·p1.00:   22.249 ms/op

Iteration   2: 3.201 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.811 ms/op
                 existUser·p0.50:   3.158 ms/op
                 existUser·p0.90:   3.449 ms/op
                 existUser·p0.95:   3.809 ms/op
                 existUser·p0.99:   5.743 ms/op
                 existUser·p0.999:  17.072 ms/op
                 existUser·p0.9999: 22.151 ms/op
                 existUser·p1.00:   22.774 ms/op

Iteration   3: 3.132 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.397 ms/op
                 existUser·p0.50:   3.068 ms/op
                 existUser·p0.90:   3.441 ms/op
                 existUser·p0.95:   3.662 ms/op
                 existUser·p0.99:   5.161 ms/op
                 existUser·p0.999:  15.729 ms/op
                 existUser·p0.9999: 20.867 ms/op
                 existUser·p1.00:   22.249 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 301188
  mean =      3.186 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19252 
    [ 2.500,  5.000) = 276870 
    [ 5.000,  7.500) = 4123 
    [ 7.500, 10.000) = 337 
    [10.000, 12.500) = 212 
    [12.500, 15.000) = 80 
    [15.000, 17.500) = 81 
    [17.500, 20.000) = 69 
    [20.000, 22.500) = 159 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.811 ms/op
     p(50.0000) =      3.146 ms/op
     p(90.0000) =      3.473 ms/op
     p(95.0000) =      3.736 ms/op
     p(99.0000) =      5.538 ms/op
     p(99.9000) =     15.729 ms/op
     p(99.9900) =     21.721 ms/op
     p(99.9990) =     22.708 ms/op
     p(99.9999) =     22.774 ms/op
    p(100.0000) =     22.774 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 8.436 ±(99.9%) 0.096 ms/op
# Warmup Iteration   2: 3.686 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.353 ±(99.9%) 0.010 ms/op
Iteration   1: 3.350 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.413 ms/op
                 getUser·p0.50:   3.187 ms/op
                 getUser·p0.90:   3.690 ms/op
                 getUser·p0.95:   4.407 ms/op
                 getUser·p0.99:   6.832 ms/op
                 getUser·p0.999:  19.562 ms/op
                 getUser·p0.9999: 23.003 ms/op
                 getUser·p1.00:   23.560 ms/op

Iteration   2: 3.342 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.126 ms/op
                 getUser·p0.50:   3.281 ms/op
                 getUser·p0.90:   3.699 ms/op
                 getUser·p0.95:   3.887 ms/op
                 getUser·p0.99:   5.257 ms/op
                 getUser·p0.999:  21.153 ms/op
                 getUser·p0.9999: 24.805 ms/op
                 getUser·p1.00:   25.068 ms/op

Iteration   3: 3.372 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.818 ms/op
                 getUser·p0.50:   3.305 ms/op
                 getUser·p0.90:   3.805 ms/op
                 getUser·p0.95:   4.182 ms/op
                 getUser·p0.99:   6.300 ms/op
                 getUser·p0.999:  15.778 ms/op
                 getUser·p0.9999: 23.904 ms/op
                 getUser·p1.00:   24.904 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 286185
  mean =      3.355 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10830 
    [ 2.500,  5.000) = 268107 
    [ 5.000,  7.500) = 6120 
    [ 7.500, 10.000) = 537 
    [10.000, 12.500) = 216 
    [12.500, 15.000) = 83 
    [15.000, 17.500) = 35 
    [17.500, 20.000) = 45 
    [20.000, 22.500) = 83 
    [22.500, 25.000) = 127 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.818 ms/op
     p(50.0000) =      3.260 ms/op
     p(90.0000) =      3.731 ms/op
     p(95.0000) =      4.076 ms/op
     p(99.0000) =      6.504 ms/op
     p(99.9000) =     15.936 ms/op
     p(99.9900) =     24.347 ms/op
     p(99.9990) =     24.917 ms/op
     p(99.9999) =     25.068 ms/op
    p(100.0000) =     25.068 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 10.325 ±(99.9%) 0.138 ms/op
# Warmup Iteration   2: 4.135 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.974 ±(99.9%) 0.012 ms/op
Iteration   1: 3.833 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.923 ms/op
                 listUser·p0.50:   3.715 ms/op
                 listUser·p0.90:   4.190 ms/op
                 listUser·p0.95:   4.399 ms/op
                 listUser·p0.99:   6.873 ms/op
                 listUser·p0.999:  15.942 ms/op
                 listUser·p0.9999: 21.756 ms/op
                 listUser·p1.00:   22.544 ms/op

Iteration   2: 3.858 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.273 ms/op
                 listUser·p0.50:   3.756 ms/op
                 listUser·p0.90:   4.174 ms/op
                 listUser·p0.95:   4.391 ms/op
                 listUser·p0.99:   6.676 ms/op
                 listUser·p0.999:  14.491 ms/op
                 listUser·p0.9999: 24.707 ms/op
                 listUser·p1.00:   24.805 ms/op

Iteration   3: 3.813 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.688 ms/op
                 listUser·p0.50:   3.740 ms/op
                 listUser·p0.90:   4.145 ms/op
                 listUser·p0.95:   4.358 ms/op
                 listUser·p0.99:   6.472 ms/op
                 listUser·p0.999:  13.124 ms/op
                 listUser·p0.9999: 15.909 ms/op
                 listUser·p1.00:   16.269 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 250127
  mean =      3.835 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 76 
    [ 2.500,  5.000) = 243887 
    [ 5.000,  7.500) = 4592 
    [ 7.500, 10.000) = 774 
    [10.000, 12.500) = 308 
    [12.500, 15.000) = 295 
    [15.000, 17.500) = 78 
    [17.500, 20.000) = 58 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 33 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.688 ms/op
     p(50.0000) =      3.736 ms/op
     p(90.0000) =      4.170 ms/op
     p(95.0000) =      4.383 ms/op
     p(99.0000) =      6.668 ms/op
     p(99.9000) =     13.992 ms/op
     p(99.9900) =     23.527 ms/op
     p(99.9990) =     24.740 ms/op
     p(99.9999) =     24.805 ms/op
    p(100.0000) =     24.805 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.655 ± 4.064  ops/ms
ClientPb.existUser                       thrpt       3  10.185 ± 3.419  ops/ms
ClientPb.getUser                         thrpt       3   9.777 ± 4.203  ops/ms
ClientPb.listUser                        thrpt       3   8.269 ± 2.998  ops/ms
ClientPb.createUser                       avgt       3   3.255 ± 1.529   ms/op
ClientPb.existUser                        avgt       3   3.157 ± 1.125   ms/op
ClientPb.getUser                          avgt       3   3.219 ± 1.108   ms/op
ClientPb.listUser                         avgt       3   3.839 ± 0.278   ms/op
ClientPb.createUser                     sample  289557   3.313 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.949           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.265           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.736           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.985           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.374           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.170           ms/op
ClientPb.createUser:createUser·p0.9999  sample          26.971           ms/op
ClientPb.createUser:createUser·p1.00    sample          29.557           ms/op
ClientPb.existUser                      sample  301188   3.186 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.811           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.146           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.473           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.736           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.538           ms/op
ClientPb.existUser:existUser·p0.999     sample          15.729           ms/op
ClientPb.existUser:existUser·p0.9999    sample          21.721           ms/op
ClientPb.existUser:existUser·p1.00      sample          22.774           ms/op
ClientPb.getUser                        sample  286185   3.355 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.818           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.260           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.731           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.076           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.504           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.936           ms/op
ClientPb.getUser:getUser·p0.9999        sample          24.347           ms/op
ClientPb.getUser:getUser·p1.00          sample          25.068           ms/op
ClientPb.listUser                       sample  250127   3.835 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.688           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.736           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.170           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.383           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.668           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.992           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.527           ms/op
ClientPb.listUser:listUser·p1.00        sample          24.805           ms/op
