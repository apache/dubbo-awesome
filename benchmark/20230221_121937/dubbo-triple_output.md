# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.633 ops/ms
# Warmup Iteration   2: 6.686 ops/ms
# Warmup Iteration   3: 9.544 ops/ms
Iteration   1: 9.921 ops/ms
Iteration   2: 9.813 ops/ms
Iteration   3: 10.047 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.927 ±(99.9%) 2.143 ops/ms [Average]
  (min, avg, max) = (9.813, 9.927, 10.047), stdev = 0.117
  CI (99.9%): [7.784, 12.070] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 3.875 ops/ms
# Warmup Iteration   2: 9.325 ops/ms
# Warmup Iteration   3: 10.033 ops/ms
Iteration   1: 10.150 ops/ms
Iteration   2: 10.049 ops/ms
Iteration   3: 9.973 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.058 ±(99.9%) 1.621 ops/ms [Average]
  (min, avg, max) = (9.973, 10.058, 10.150), stdev = 0.089
  CI (99.9%): [8.436, 11.679] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.344 ops/ms
# Warmup Iteration   2: 8.894 ops/ms
# Warmup Iteration   3: 9.767 ops/ms
Iteration   1: 9.740 ops/ms
Iteration   2: 9.601 ops/ms
Iteration   3: 10.244 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.862 ±(99.9%) 6.171 ops/ms [Average]
  (min, avg, max) = (9.601, 9.862, 10.244), stdev = 0.338
  CI (99.9%): [3.690, 16.033] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.423 ops/ms
# Warmup Iteration   2: 7.712 ops/ms
# Warmup Iteration   3: 8.484 ops/ms
Iteration   1: 8.681 ops/ms
Iteration   2: 8.204 ops/ms
Iteration   3: 8.249 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.378 ±(99.9%) 4.802 ops/ms [Average]
  (min, avg, max) = (8.204, 8.378, 8.681), stdev = 0.263
  CI (99.9%): [3.576, 13.180] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 8.154 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.440 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.443 ±(99.9%) 0.003 ms/op
Iteration   1: 3.176 ±(99.9%) 0.004 ms/op
Iteration   2: 3.241 ±(99.9%) 0.004 ms/op
Iteration   3: 3.084 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.167 ±(99.9%) 1.436 ms/op [Average]
  (min, avg, max) = (3.084, 3.167, 3.241), stdev = 0.079
  CI (99.9%): [1.730, 4.603] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 7.993 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.269 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.161 ±(99.9%) 0.004 ms/op
Iteration   1: 3.139 ±(99.9%) 0.008 ms/op
Iteration   2: 3.017 ±(99.9%) 0.009 ms/op
Iteration   3: 3.033 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.063 ±(99.9%) 1.213 ms/op [Average]
  (min, avg, max) = (3.017, 3.063, 3.139), stdev = 0.066
  CI (99.9%): [1.850, 4.276] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 7.197 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.337 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.276 ±(99.9%) 0.007 ms/op
Iteration   1: 3.282 ±(99.9%) 0.005 ms/op
Iteration   2: 3.109 ±(99.9%) 0.005 ms/op
Iteration   3: 3.185 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.192 ±(99.9%) 1.587 ms/op [Average]
  (min, avg, max) = (3.109, 3.192, 3.282), stdev = 0.087
  CI (99.9%): [1.605, 4.779] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 10.071 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 4.145 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.806 ±(99.9%) 0.007 ms/op
Iteration   1: 3.716 ±(99.9%) 0.008 ms/op
Iteration   2: 3.769 ±(99.9%) 0.003 ms/op
Iteration   3: 3.730 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.738 ±(99.9%) 0.494 ms/op [Average]
  (min, avg, max) = (3.716, 3.738, 3.769), stdev = 0.027
  CI (99.9%): [3.244, 4.233] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 7.322 ±(99.9%) 0.086 ms/op
# Warmup Iteration   2: 3.639 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.243 ±(99.9%) 0.009 ms/op
Iteration   1: 3.136 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.037 ms/op
                 createUser·p0.50:   3.133 ms/op
                 createUser·p0.90:   3.383 ms/op
                 createUser·p0.95:   3.707 ms/op
                 createUser·p0.99:   5.341 ms/op
                 createUser·p0.999:  10.289 ms/op
                 createUser·p0.9999: 21.882 ms/op
                 createUser·p1.00:   22.282 ms/op

Iteration   2: 3.189 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.153 ms/op
                 createUser·p0.50:   3.043 ms/op
                 createUser·p0.90:   3.695 ms/op
                 createUser·p0.95:   4.227 ms/op
                 createUser·p0.99:   5.546 ms/op
                 createUser·p0.999:  18.369 ms/op
                 createUser·p0.9999: 23.036 ms/op
                 createUser·p1.00:   23.527 ms/op

Iteration   3: 3.127 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.366 ms/op
                 createUser·p0.50:   3.043 ms/op
                 createUser·p0.90:   3.478 ms/op
                 createUser·p0.95:   3.731 ms/op
                 createUser·p0.99:   5.589 ms/op
                 createUser·p0.999:  15.516 ms/op
                 createUser·p0.9999: 18.134 ms/op
                 createUser·p1.00:   19.923 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 304746
  mean =      3.150 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19905 
    [ 2.500,  5.000) = 279594 
    [ 5.000,  7.500) = 4524 
    [ 7.500, 10.000) = 278 
    [10.000, 12.500) = 81 
    [12.500, 15.000) = 27 
    [15.000, 17.500) = 88 
    [17.500, 20.000) = 134 
    [20.000, 22.500) = 92 
    [22.500, 25.000) = 23 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.037 ms/op
     p(50.0000) =      3.092 ms/op
     p(90.0000) =      3.506 ms/op
     p(95.0000) =      3.903 ms/op
     p(99.0000) =      5.464 ms/op
     p(99.9000) =     15.589 ms/op
     p(99.9900) =     22.020 ms/op
     p(99.9990) =     23.329 ms/op
     p(99.9999) =     23.527 ms/op
    p(100.0000) =     23.527 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 6.409 ±(99.9%) 0.077 ms/op
# Warmup Iteration   2: 3.244 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.173 ±(99.9%) 0.008 ms/op
Iteration   1: 3.188 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.171 ms/op
                 existUser·p0.50:   3.084 ms/op
                 existUser·p0.90:   3.936 ms/op
                 existUser·p0.95:   4.137 ms/op
                 existUser·p0.99:   5.874 ms/op
                 existUser·p0.999:  9.568 ms/op
                 existUser·p0.9999: 19.889 ms/op
                 existUser·p1.00:   20.349 ms/op

Iteration   2: 2.969 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.544 ms/op
                 existUser·p0.50:   2.908 ms/op
                 existUser·p0.90:   3.146 ms/op
                 existUser·p0.95:   3.363 ms/op
                 existUser·p0.99:   5.128 ms/op
                 existUser·p0.999:  8.166 ms/op
                 existUser·p0.9999: 21.660 ms/op
                 existUser·p1.00:   22.938 ms/op

Iteration   3: 3.115 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.321 ms/op
                 existUser·p0.50:   3.133 ms/op
                 existUser·p0.90:   3.256 ms/op
                 existUser·p0.95:   3.490 ms/op
                 existUser·p0.99:   5.104 ms/op
                 existUser·p0.999:  13.556 ms/op
                 existUser·p0.9999: 20.480 ms/op
                 existUser·p1.00:   21.234 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 310746
  mean =      3.088 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 28519 
    [ 2.500,  5.000) = 276701 
    [ 5.000,  7.500) = 4830 
    [ 7.500, 10.000) = 263 
    [10.000, 12.500) = 134 
    [12.500, 15.000) = 8 
    [15.000, 17.500) = 45 
    [17.500, 20.000) = 140 
    [20.000, 22.500) = 102 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.171 ms/op
     p(50.0000) =      3.060 ms/op
     p(90.0000) =      3.281 ms/op
     p(95.0000) =      3.931 ms/op
     p(99.0000) =      5.390 ms/op
     p(99.9000) =     12.026 ms/op
     p(99.9900) =     21.168 ms/op
     p(99.9990) =     22.512 ms/op
     p(99.9999) =     22.938 ms/op
    p(100.0000) =     22.938 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 7.320 ±(99.9%) 0.087 ms/op
# Warmup Iteration   2: 3.456 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.406 ±(99.9%) 0.012 ms/op
Iteration   1: 3.160 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.163 ms/op
                 getUser·p0.50:   3.068 ms/op
                 getUser·p0.90:   3.478 ms/op
                 getUser·p0.95:   3.912 ms/op
                 getUser·p0.99:   6.210 ms/op
                 getUser·p0.999:  9.978 ms/op
                 getUser·p0.9999: 19.887 ms/op
                 getUser·p1.00:   20.611 ms/op

Iteration   2: 3.243 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.518 ms/op
                 getUser·p0.50:   3.187 ms/op
                 getUser·p0.90:   3.703 ms/op
                 getUser·p0.95:   4.071 ms/op
                 getUser·p0.99:   5.898 ms/op
                 getUser·p0.999:  9.322 ms/op
                 getUser·p0.9999: 24.973 ms/op
                 getUser·p1.00:   26.706 ms/op

Iteration   3: 3.286 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.523 ms/op
                 getUser·p0.50:   3.211 ms/op
                 getUser·p0.90:   3.883 ms/op
                 getUser·p0.95:   4.334 ms/op
                 getUser·p0.99:   5.767 ms/op
                 getUser·p0.999:  9.971 ms/op
                 getUser·p0.9999: 24.118 ms/op
                 getUser·p1.00:   24.740 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 297262
  mean =      3.229 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 25923 
    [ 2.500,  5.000) = 263298 
    [ 5.000,  7.500) = 7291 
    [ 7.500, 10.000) = 461 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 8 
    [17.500, 20.000) = 126 
    [20.000, 22.500) = 40 
    [22.500, 25.000) = 105 
    [25.000, 27.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      0.523 ms/op
     p(50.0000) =      3.166 ms/op
     p(90.0000) =      3.727 ms/op
     p(95.0000) =      4.129 ms/op
     p(99.0000) =      6.005 ms/op
     p(99.9000) =      9.961 ms/op
     p(99.9900) =     24.257 ms/op
     p(99.9990) =     25.756 ms/op
     p(99.9999) =     26.706 ms/op
    p(100.0000) =     26.706 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 8.690 ±(99.9%) 0.110 ms/op
# Warmup Iteration   2: 4.087 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.925 ±(99.9%) 0.013 ms/op
Iteration   1: 3.760 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.134 ms/op
                 listUser·p0.50:   3.592 ms/op
                 listUser·p0.90:   4.096 ms/op
                 listUser·p0.95:   4.325 ms/op
                 listUser·p0.99:   7.230 ms/op
                 listUser·p0.999:  13.367 ms/op
                 listUser·p0.9999: 23.489 ms/op
                 listUser·p1.00:   24.478 ms/op

Iteration   2: 3.678 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.146 ms/op
                 listUser·p0.50:   3.564 ms/op
                 listUser·p0.90:   3.953 ms/op
                 listUser·p0.95:   4.137 ms/op
                 listUser·p0.99:   6.373 ms/op
                 listUser·p0.999:  13.517 ms/op
                 listUser·p0.9999: 14.062 ms/op
                 listUser·p1.00:   14.205 ms/op

Iteration   3: 3.738 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.911 ms/op
                 listUser·p0.50:   3.600 ms/op
                 listUser·p0.90:   4.030 ms/op
                 listUser·p0.95:   4.317 ms/op
                 listUser·p0.99:   7.199 ms/op
                 listUser·p0.999:  13.703 ms/op
                 listUser·p0.9999: 22.264 ms/op
                 listUser·p1.00:   22.348 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 257728
  mean =      3.725 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 66 
    [ 2.500,  5.000) = 250415 
    [ 5.000,  7.500) = 5336 
    [ 7.500, 10.000) = 1313 
    [10.000, 12.500) = 208 
    [12.500, 15.000) = 257 
    [15.000, 17.500) = 5 
    [17.500, 20.000) = 12 
    [20.000, 22.500) = 100 
    [22.500, 25.000) = 16 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.911 ms/op
     p(50.0000) =      3.584 ms/op
     p(90.0000) =      4.035 ms/op
     p(95.0000) =      4.252 ms/op
     p(99.0000) =      6.971 ms/op
     p(99.9000) =     13.468 ms/op
     p(99.9900) =     22.315 ms/op
     p(99.9990) =     23.953 ms/op
     p(99.9999) =     24.478 ms/op
    p(100.0000) =     24.478 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.927 ± 2.143  ops/ms
ClientPb.existUser                       thrpt       3  10.058 ± 1.621  ops/ms
ClientPb.getUser                         thrpt       3   9.862 ± 6.171  ops/ms
ClientPb.listUser                        thrpt       3   8.378 ± 4.802  ops/ms
ClientPb.createUser                       avgt       3   3.167 ± 1.436   ms/op
ClientPb.existUser                        avgt       3   3.063 ± 1.213   ms/op
ClientPb.getUser                          avgt       3   3.192 ± 1.587   ms/op
ClientPb.listUser                         avgt       3   3.738 ± 0.494   ms/op
ClientPb.createUser                     sample  304746   3.150 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.037           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.092           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.506           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.903           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.464           ms/op
ClientPb.createUser:createUser·p0.999   sample          15.589           ms/op
ClientPb.createUser:createUser·p0.9999  sample          22.020           ms/op
ClientPb.createUser:createUser·p1.00    sample          23.527           ms/op
ClientPb.existUser                      sample  310746   3.088 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.171           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.060           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.281           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.931           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.390           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.026           ms/op
ClientPb.existUser:existUser·p0.9999    sample          21.168           ms/op
ClientPb.existUser:existUser·p1.00      sample          22.938           ms/op
ClientPb.getUser                        sample  297262   3.229 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.523           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.166           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.727           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.129           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.005           ms/op
ClientPb.getUser:getUser·p0.999         sample           9.961           ms/op
ClientPb.getUser:getUser·p0.9999        sample          24.257           ms/op
ClientPb.getUser:getUser·p1.00          sample          26.706           ms/op
ClientPb.listUser                       sample  257728   3.725 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.911           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.584           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.035           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.252           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.971           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.468           ms/op
ClientPb.listUser:listUser·p0.9999      sample          22.315           ms/op
ClientPb.listUser:listUser·p1.00        sample          24.478           ms/op
