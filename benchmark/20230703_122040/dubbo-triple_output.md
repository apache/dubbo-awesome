# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.467 ops/ms
# Warmup Iteration   2: 5.768 ops/ms
# Warmup Iteration   3: 9.257 ops/ms
Iteration   1: 9.792 ops/ms
Iteration   2: 9.777 ops/ms
Iteration   3: 9.917 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.829 ±(99.9%) 1.399 ops/ms [Average]
  (min, avg, max) = (9.777, 9.829, 9.917), stdev = 0.077
  CI (99.9%): [8.430, 11.228] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 3.617 ops/ms
# Warmup Iteration   2: 9.235 ops/ms
# Warmup Iteration   3: 9.987 ops/ms
Iteration   1: 10.127 ops/ms
Iteration   2: 10.526 ops/ms
Iteration   3: 10.278 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.310 ±(99.9%) 3.679 ops/ms [Average]
  (min, avg, max) = (10.127, 10.310, 10.526), stdev = 0.202
  CI (99.9%): [6.631, 13.990] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.651 ops/ms
# Warmup Iteration   2: 8.976 ops/ms
# Warmup Iteration   3: 9.806 ops/ms
Iteration   1: 9.756 ops/ms
Iteration   2: 10.119 ops/ms
Iteration   3: 10.230 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.035 ±(99.9%) 4.516 ops/ms [Average]
  (min, avg, max) = (9.756, 10.035, 10.230), stdev = 0.248
  CI (99.9%): [5.519, 14.551] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.359 ops/ms
# Warmup Iteration   2: 7.648 ops/ms
# Warmup Iteration   3: 8.634 ops/ms
Iteration   1: 8.432 ops/ms
Iteration   2: 8.373 ops/ms
Iteration   3: 8.542 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.449 ±(99.9%) 1.570 ops/ms [Average]
  (min, avg, max) = (8.373, 8.449, 8.542), stdev = 0.086
  CI (99.9%): [6.879, 10.019] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 7.597 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.516 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.430 ±(99.9%) 0.006 ms/op
Iteration   1: 3.373 ±(99.9%) 0.007 ms/op
Iteration   2: 3.476 ±(99.9%) 0.005 ms/op
Iteration   3: 3.206 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.352 ±(99.9%) 2.486 ms/op [Average]
  (min, avg, max) = (3.206, 3.352, 3.476), stdev = 0.136
  CI (99.9%): [0.865, 5.838] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 7.376 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.234 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.080 ±(99.9%) 0.005 ms/op
Iteration   1: 3.141 ±(99.9%) 0.008 ms/op
Iteration   2: 3.203 ±(99.9%) 0.002 ms/op
Iteration   3: 3.116 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.153 ±(99.9%) 0.816 ms/op [Average]
  (min, avg, max) = (3.116, 3.153, 3.203), stdev = 0.045
  CI (99.9%): [2.337, 3.969] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 8.151 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.355 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.409 ±(99.9%) 0.007 ms/op
Iteration   1: 3.389 ±(99.9%) 0.006 ms/op
Iteration   2: 3.149 ±(99.9%) 0.003 ms/op
Iteration   3: 3.152 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.230 ±(99.9%) 2.513 ms/op [Average]
  (min, avg, max) = (3.149, 3.230, 3.389), stdev = 0.138
  CI (99.9%): [0.717, 5.743] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 9.569 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 4.406 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 4.006 ±(99.9%) 0.004 ms/op
Iteration   1: 3.781 ±(99.9%) 0.010 ms/op
Iteration   2: 3.854 ±(99.9%) 0.006 ms/op
Iteration   3: 3.735 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.790 ±(99.9%) 1.094 ms/op [Average]
  (min, avg, max) = (3.735, 3.790, 3.854), stdev = 0.060
  CI (99.9%): [2.695, 4.884] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 7.296 ±(99.9%) 0.095 ms/op
# Warmup Iteration   2: 3.650 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.428 ±(99.9%) 0.009 ms/op
Iteration   1: 3.187 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.038 ms/op
                 createUser·p0.50:   3.047 ms/op
                 createUser·p0.90:   3.600 ms/op
                 createUser·p0.95:   3.891 ms/op
                 createUser·p0.99:   5.415 ms/op
                 createUser·p0.999:  19.235 ms/op
                 createUser·p0.9999: 23.363 ms/op
                 createUser·p1.00:   24.904 ms/op

Iteration   2: 3.415 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.326 ms/op
                 createUser·p0.50:   3.273 ms/op
                 createUser·p0.90:   4.018 ms/op
                 createUser·p0.95:   4.415 ms/op
                 createUser·p0.99:   5.768 ms/op
                 createUser·p0.999:  18.914 ms/op
                 createUser·p0.9999: 23.732 ms/op
                 createUser·p1.00:   24.871 ms/op

Iteration   3: 3.195 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.374 ms/op
                 createUser·p0.50:   3.174 ms/op
                 createUser·p0.90:   3.330 ms/op
                 createUser·p0.95:   3.621 ms/op
                 createUser·p0.99:   5.906 ms/op
                 createUser·p0.999:  15.186 ms/op
                 createUser·p0.9999: 20.546 ms/op
                 createUser·p1.00:   20.611 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 294155
  mean =      3.262 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20952 
    [ 2.500,  5.000) = 266025 
    [ 5.000,  7.500) = 6269 
    [ 7.500, 10.000) = 466 
    [10.000, 12.500) = 54 
    [12.500, 15.000) = 41 
    [15.000, 17.500) = 64 
    [17.500, 20.000) = 115 
    [20.000, 22.500) = 118 
    [22.500, 25.000) = 51 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.326 ms/op
     p(50.0000) =      3.187 ms/op
     p(90.0000) =      3.752 ms/op
     p(95.0000) =      4.096 ms/op
     p(99.0000) =      5.726 ms/op
     p(99.9000) =     16.470 ms/op
     p(99.9900) =     23.462 ms/op
     p(99.9990) =     24.871 ms/op
     p(99.9999) =     24.904 ms/op
    p(100.0000) =     24.904 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 7.497 ±(99.9%) 0.083 ms/op
# Warmup Iteration   2: 3.303 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.088 ±(99.9%) 0.007 ms/op
Iteration   1: 3.070 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.998 ms/op
                 existUser·p0.50:   2.966 ms/op
                 existUser·p0.90:   3.248 ms/op
                 existUser·p0.95:   3.482 ms/op
                 existUser·p0.99:   5.685 ms/op
                 existUser·p0.999:  9.217 ms/op
                 existUser·p0.9999: 19.928 ms/op
                 existUser·p1.00:   20.349 ms/op

Iteration   2: 3.127 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.730 ms/op
                 existUser·p0.50:   3.146 ms/op
                 existUser·p0.90:   3.269 ms/op
                 existUser·p0.95:   3.351 ms/op
                 existUser·p0.99:   5.431 ms/op
                 existUser·p0.999:  8.454 ms/op
                 existUser·p0.9999: 22.242 ms/op
                 existUser·p1.00:   23.003 ms/op

Iteration   3: 3.029 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   1.288 ms/op
                 existUser·p0.50:   2.966 ms/op
                 existUser·p0.90:   3.158 ms/op
                 existUser·p0.95:   3.387 ms/op
                 existUser·p0.99:   5.325 ms/op
                 existUser·p0.999:  10.945 ms/op
                 existUser·p0.9999: 20.298 ms/op
                 existUser·p1.00:   21.168 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 311892
  mean =      3.075 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22748 
    [ 2.500,  5.000) = 282739 
    [ 5.000,  7.500) = 5770 
    [ 7.500, 10.000) = 321 
    [10.000, 12.500) = 25 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 40 
    [17.500, 20.000) = 114 
    [20.000, 22.500) = 101 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.730 ms/op
     p(50.0000) =      3.035 ms/op
     p(90.0000) =      3.248 ms/op
     p(95.0000) =      3.408 ms/op
     p(99.0000) =      5.431 ms/op
     p(99.9000) =     10.160 ms/op
     p(99.9900) =     21.332 ms/op
     p(99.9990) =     22.475 ms/op
     p(99.9999) =     23.003 ms/op
    p(100.0000) =     23.003 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 8.279 ±(99.9%) 0.102 ms/op
# Warmup Iteration   2: 3.572 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.272 ±(99.9%) 0.010 ms/op
Iteration   1: 3.266 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.360 ms/op
                 getUser·p0.50:   3.138 ms/op
                 getUser·p0.90:   3.777 ms/op
                 getUser·p0.95:   4.481 ms/op
                 getUser·p0.99:   6.021 ms/op
                 getUser·p0.999:  16.499 ms/op
                 getUser·p0.9999: 20.486 ms/op
                 getUser·p1.00:   24.773 ms/op

Iteration   2: 3.150 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.341 ms/op
                 getUser·p0.50:   3.056 ms/op
                 getUser·p0.90:   3.498 ms/op
                 getUser·p0.95:   3.875 ms/op
                 getUser·p0.99:   5.341 ms/op
                 getUser·p0.999:  9.748 ms/op
                 getUser·p0.9999: 20.311 ms/op
                 getUser·p1.00:   20.808 ms/op

Iteration   3: 3.186 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.485 ms/op
                 getUser·p0.50:   3.068 ms/op
                 getUser·p0.90:   3.486 ms/op
                 getUser·p0.95:   3.674 ms/op
                 getUser·p0.99:   5.816 ms/op
                 getUser·p0.999:  10.125 ms/op
                 getUser·p0.9999: 21.558 ms/op
                 getUser·p1.00:   22.610 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 299711
  mean =      3.200 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14110 
    [ 2.500,  5.000) = 278798 
    [ 5.000,  7.500) = 5969 
    [ 7.500, 10.000) = 403 
    [10.000, 12.500) = 105 
    [12.500, 15.000) = 6 
    [15.000, 17.500) = 89 
    [17.500, 20.000) = 161 
    [20.000, 22.500) = 62 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.341 ms/op
     p(50.0000) =      3.088 ms/op
     p(90.0000) =      3.555 ms/op
     p(95.0000) =      4.035 ms/op
     p(99.0000) =      5.628 ms/op
     p(99.9000) =     15.956 ms/op
     p(99.9900) =     20.873 ms/op
     p(99.9990) =     22.614 ms/op
     p(99.9999) =     24.773 ms/op
    p(100.0000) =     24.773 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 9.039 ±(99.9%) 0.109 ms/op
# Warmup Iteration   2: 4.195 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.845 ±(99.9%) 0.012 ms/op
Iteration   1: 3.825 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.724 ms/op
                 listUser·p0.50:   3.637 ms/op
                 listUser·p0.90:   4.121 ms/op
                 listUser·p0.95:   4.719 ms/op
                 listUser·p0.99:   7.487 ms/op
                 listUser·p0.999:  17.161 ms/op
                 listUser·p0.9999: 21.627 ms/op
                 listUser·p1.00:   23.888 ms/op

Iteration   2: 3.699 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.363 ms/op
                 listUser·p0.50:   3.600 ms/op
                 listUser·p0.90:   3.944 ms/op
                 listUser·p0.95:   4.157 ms/op
                 listUser·p0.99:   6.996 ms/op
                 listUser·p0.999:  12.747 ms/op
                 listUser·p0.9999: 18.842 ms/op
                 listUser·p1.00:   18.907 ms/op

Iteration   3: 3.878 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.559 ms/op
                 listUser·p0.50:   3.703 ms/op
                 listUser·p0.90:   4.211 ms/op
                 listUser·p0.95:   4.925 ms/op
                 listUser·p0.99:   7.569 ms/op
                 listUser·p0.999:  12.845 ms/op
                 listUser·p0.9999: 16.909 ms/op
                 listUser·p1.00:   16.974 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 252537
  mean =      3.799 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 75 
    [ 2.500,  5.000) = 242986 
    [ 5.000,  7.500) = 7138 
    [ 7.500, 10.000) = 1643 
    [10.000, 12.500) = 313 
    [12.500, 15.000) = 208 
    [15.000, 17.500) = 72 
    [17.500, 20.000) = 64 
    [20.000, 22.500) = 37 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.559 ms/op
     p(50.0000) =      3.637 ms/op
     p(90.0000) =      4.108 ms/op
     p(95.0000) =      4.456 ms/op
     p(99.0000) =      7.315 ms/op
     p(99.9000) =     13.361 ms/op
     p(99.9900) =     20.865 ms/op
     p(99.9990) =     21.822 ms/op
     p(99.9999) =     23.888 ms/op
    p(100.0000) =     23.888 ms/op


# Run complete. Total time: 00:13:07

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.829 ± 1.399  ops/ms
ClientPb.existUser                       thrpt       3  10.310 ± 3.679  ops/ms
ClientPb.getUser                         thrpt       3  10.035 ± 4.516  ops/ms
ClientPb.listUser                        thrpt       3   8.449 ± 1.570  ops/ms
ClientPb.createUser                       avgt       3   3.352 ± 2.486   ms/op
ClientPb.existUser                        avgt       3   3.153 ± 0.816   ms/op
ClientPb.getUser                          avgt       3   3.230 ± 2.513   ms/op
ClientPb.listUser                         avgt       3   3.790 ± 1.094   ms/op
ClientPb.createUser                     sample  294155   3.262 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.326           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.187           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.752           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.096           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.726           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.470           ms/op
ClientPb.createUser:createUser·p0.9999  sample          23.462           ms/op
ClientPb.createUser:createUser·p1.00    sample          24.904           ms/op
ClientPb.existUser                      sample  311892   3.075 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.730           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.035           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.248           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.408           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.431           ms/op
ClientPb.existUser:existUser·p0.999     sample          10.160           ms/op
ClientPb.existUser:existUser·p0.9999    sample          21.332           ms/op
ClientPb.existUser:existUser·p1.00      sample          23.003           ms/op
ClientPb.getUser                        sample  299711   3.200 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.341           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.088           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.555           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.035           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.628           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.956           ms/op
ClientPb.getUser:getUser·p0.9999        sample          20.873           ms/op
ClientPb.getUser:getUser·p1.00          sample          24.773           ms/op
ClientPb.listUser                       sample  252537   3.799 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.559           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.637           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.108           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.456           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.315           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.361           ms/op
ClientPb.listUser:listUser·p0.9999      sample          20.865           ms/op
ClientPb.listUser:listUser·p1.00        sample          23.888           ms/op
