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
# Warmup Iteration   1: 2.045 ops/ms
# Warmup Iteration   2: 5.472 ops/ms
# Warmup Iteration   3: 8.486 ops/ms
Iteration   1: 8.972 ops/ms
Iteration   2: 8.976 ops/ms
Iteration   3: 9.062 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.003 ±(99.9%) 0.934 ops/ms [Average]
  (min, avg, max) = (8.972, 9.003, 9.062), stdev = 0.051
  CI (99.9%): [8.070, 9.937] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 3.213 ops/ms
# Warmup Iteration   2: 8.794 ops/ms
# Warmup Iteration   3: 9.396 ops/ms
Iteration   1: 9.508 ops/ms
Iteration   2: 9.591 ops/ms
Iteration   3: 9.763 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.620 ±(99.9%) 2.370 ops/ms [Average]
  (min, avg, max) = (9.508, 9.620, 9.763), stdev = 0.130
  CI (99.9%): [7.250, 11.991] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 2.957 ops/ms
# Warmup Iteration   2: 8.682 ops/ms
# Warmup Iteration   3: 8.988 ops/ms
Iteration   1: 9.244 ops/ms
Iteration   2: 9.270 ops/ms
Iteration   3: 9.249 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.254 ±(99.9%) 0.248 ops/ms [Average]
  (min, avg, max) = (9.244, 9.254, 9.270), stdev = 0.014
  CI (99.9%): [9.006, 9.503] (assumes normal distribution)


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
# Warmup Iteration   1: 2.743 ops/ms
# Warmup Iteration   2: 7.161 ops/ms
# Warmup Iteration   3: 7.624 ops/ms
Iteration   1: 7.840 ops/ms
Iteration   2: 7.618 ops/ms
Iteration   3: 7.680 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.713 ±(99.9%) 2.089 ops/ms [Average]
  (min, avg, max) = (7.618, 7.713, 7.840), stdev = 0.115
  CI (99.9%): [5.624, 9.802] (assumes normal distribution)


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
# Warmup Iteration   1: 10.360 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.704 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.698 ±(99.9%) 0.004 ms/op
Iteration   1: 3.576 ±(99.9%) 0.003 ms/op
Iteration   2: 3.479 ±(99.9%) 0.003 ms/op
Iteration   3: 3.534 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.530 ±(99.9%) 0.896 ms/op [Average]
  (min, avg, max) = (3.479, 3.530, 3.576), stdev = 0.049
  CI (99.9%): [2.634, 4.425] (assumes normal distribution)


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
# Warmup Iteration   1: 9.818 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.556 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.429 ±(99.9%) 0.004 ms/op
Iteration   1: 3.444 ±(99.9%) 0.005 ms/op
Iteration   2: 3.356 ±(99.9%) 0.003 ms/op
Iteration   3: 3.361 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.387 ±(99.9%) 0.908 ms/op [Average]
  (min, avg, max) = (3.356, 3.387, 3.444), stdev = 0.050
  CI (99.9%): [2.479, 4.295] (assumes normal distribution)


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
# Warmup Iteration   1: 8.285 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.662 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.599 ±(99.9%) 0.003 ms/op
Iteration   1: 3.471 ±(99.9%) 0.007 ms/op
Iteration   2: 3.456 ±(99.9%) 0.004 ms/op
Iteration   3: 3.436 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.454 ±(99.9%) 0.322 ms/op [Average]
  (min, avg, max) = (3.436, 3.454, 3.471), stdev = 0.018
  CI (99.9%): [3.132, 3.776] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 10.341 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 4.402 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.322 ±(99.9%) 0.004 ms/op
Iteration   1: 4.227 ±(99.9%) 0.005 ms/op
Iteration   2: 4.145 ±(99.9%) 0.006 ms/op
Iteration   3: 4.206 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.193 ±(99.9%) 0.781 ms/op [Average]
  (min, avg, max) = (4.145, 4.193, 4.227), stdev = 0.043
  CI (99.9%): [3.412, 4.973] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 10.055 ±(99.9%) 0.121 ms/op
# Warmup Iteration   2: 4.117 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.581 ±(99.9%) 0.010 ms/op
Iteration   1: 3.649 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.382 ms/op
                 createUser·p0.50:   3.400 ms/op
                 createUser·p0.90:   4.260 ms/op
                 createUser·p0.95:   5.743 ms/op
                 createUser·p0.99:   7.392 ms/op
                 createUser·p0.999:  19.472 ms/op
                 createUser·p0.9999: 22.479 ms/op
                 createUser·p1.00:   23.298 ms/op

Iteration   2: 3.481 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.309 ms/op
                 createUser·p0.50:   3.383 ms/op
                 createUser·p0.90:   3.949 ms/op
                 createUser·p0.95:   4.219 ms/op
                 createUser·p0.99:   5.833 ms/op
                 createUser·p0.999:  21.597 ms/op
                 createUser·p0.9999: 25.056 ms/op
                 createUser·p1.00:   25.592 ms/op

Iteration   3: 3.496 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.022 ms/op
                 createUser·p0.50:   3.379 ms/op
                 createUser·p0.90:   3.985 ms/op
                 createUser·p0.95:   4.252 ms/op
                 createUser·p0.99:   5.445 ms/op
                 createUser·p0.999:  18.110 ms/op
                 createUser·p0.9999: 29.781 ms/op
                 createUser·p1.00:   31.130 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 271112
  mean =      3.541 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7136 
    [ 2.500,  5.000) = 254965 
    [ 5.000,  7.500) = 7608 
    [ 7.500, 10.000) = 806 
    [10.000, 12.500) = 243 
    [12.500, 15.000) = 25 
    [15.000, 17.500) = 18 
    [17.500, 20.000) = 69 
    [20.000, 22.500) = 103 
    [22.500, 25.000) = 98 
    [25.000, 27.500) = 20 
    [27.500, 30.000) = 13 
    [30.000, 32.500) = 8 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.022 ms/op
     p(50.0000) =      3.387 ms/op
     p(90.0000) =      4.030 ms/op
     p(95.0000) =      4.407 ms/op
     p(99.0000) =      6.914 ms/op
     p(99.9000) =     19.268 ms/op
     p(99.9900) =     26.145 ms/op
     p(99.9990) =     30.648 ms/op
     p(99.9999) =     31.130 ms/op
    p(100.0000) =     31.130 ms/op


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
# Warmup Iteration   1: 9.777 ±(99.9%) 0.129 ms/op
# Warmup Iteration   2: 3.663 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.410 ±(99.9%) 0.008 ms/op
Iteration   1: 3.343 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.321 ms/op
                 existUser·p0.50:   3.215 ms/op
                 existUser·p0.90:   3.793 ms/op
                 existUser·p0.95:   4.080 ms/op
                 existUser·p0.99:   5.431 ms/op
                 existUser·p0.999:  18.655 ms/op
                 existUser·p0.9999: 22.395 ms/op
                 existUser·p1.00:   22.938 ms/op

Iteration   2: 3.316 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.104 ms/op
                 existUser·p0.50:   3.170 ms/op
                 existUser·p0.90:   3.682 ms/op
                 existUser·p0.95:   3.981 ms/op
                 existUser·p0.99:   5.890 ms/op
                 existUser·p0.999:  20.479 ms/op
                 existUser·p0.9999: 23.932 ms/op
                 existUser·p1.00:   25.002 ms/op

Iteration   3: 3.424 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.405 ms/op
                 existUser·p0.50:   3.289 ms/op
                 existUser·p0.90:   3.920 ms/op
                 existUser·p0.95:   4.227 ms/op
                 existUser·p0.99:   5.890 ms/op
                 existUser·p0.999:  19.800 ms/op
                 existUser·p0.9999: 25.908 ms/op
                 existUser·p1.00:   26.608 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 285700
  mean =      3.360 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4784 
    [ 2.500,  5.000) = 276322 
    [ 5.000,  7.500) = 3616 
    [ 7.500, 10.000) = 352 
    [10.000, 12.500) = 182 
    [12.500, 15.000) = 117 
    [15.000, 17.500) = 8 
    [17.500, 20.000) = 56 
    [20.000, 22.500) = 109 
    [22.500, 25.000) = 130 
    [25.000, 27.500) = 24 

  Percentiles, ms/op:
      p(0.0000) =      1.104 ms/op
     p(50.0000) =      3.219 ms/op
     p(90.0000) =      3.817 ms/op
     p(95.0000) =      4.112 ms/op
     p(99.0000) =      5.693 ms/op
     p(99.9000) =     18.858 ms/op
     p(99.9900) =     24.670 ms/op
     p(99.9990) =     26.547 ms/op
     p(99.9999) =     26.608 ms/op
    p(100.0000) =     26.608 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 9.654 ±(99.9%) 0.134 ms/op
# Warmup Iteration   2: 3.708 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.471 ±(99.9%) 0.008 ms/op
Iteration   1: 3.488 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.296 ms/op
                 getUser·p0.50:   3.322 ms/op
                 getUser·p0.90:   3.891 ms/op
                 getUser·p0.95:   4.284 ms/op
                 getUser·p0.99:   6.659 ms/op
                 getUser·p0.999:  17.236 ms/op
                 getUser·p0.9999: 23.326 ms/op
                 getUser·p1.00:   25.231 ms/op

Iteration   2: 3.420 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.243 ms/op
                 getUser·p0.50:   3.355 ms/op
                 getUser·p0.90:   3.809 ms/op
                 getUser·p0.95:   4.022 ms/op
                 getUser·p0.99:   5.317 ms/op
                 getUser·p0.999:  17.269 ms/op
                 getUser·p0.9999: 20.304 ms/op
                 getUser·p1.00:   20.972 ms/op

Iteration   3: 3.508 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.755 ms/op
                 getUser·p0.50:   3.416 ms/op
                 getUser·p0.90:   3.887 ms/op
                 getUser·p0.95:   4.116 ms/op
                 getUser·p0.99:   6.029 ms/op
                 getUser·p0.999:  12.153 ms/op
                 getUser·p0.9999: 23.294 ms/op
                 getUser·p1.00:   24.150 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 276284
  mean =      3.472 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5129 
    [ 2.500,  5.000) = 265020 
    [ 5.000,  7.500) = 5098 
    [ 7.500, 10.000) = 517 
    [10.000, 12.500) = 166 
    [12.500, 15.000) = 55 
    [15.000, 17.500) = 86 
    [17.500, 20.000) = 128 
    [20.000, 22.500) = 45 
    [22.500, 25.000) = 39 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.243 ms/op
     p(50.0000) =      3.363 ms/op
     p(90.0000) =      3.863 ms/op
     p(95.0000) =      4.125 ms/op
     p(99.0000) =      6.062 ms/op
     p(99.9000) =     16.843 ms/op
     p(99.9900) =     23.114 ms/op
     p(99.9990) =     24.125 ms/op
     p(99.9999) =     25.231 ms/op
    p(100.0000) =     25.231 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 10.419 ±(99.9%) 0.137 ms/op
# Warmup Iteration   2: 4.498 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.311 ±(99.9%) 0.011 ms/op
Iteration   1: 4.171 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.303 ms/op
                 listUser·p0.50:   4.022 ms/op
                 listUser·p0.90:   4.579 ms/op
                 listUser·p0.95:   4.825 ms/op
                 listUser·p0.99:   7.070 ms/op
                 listUser·p0.999:  19.802 ms/op
                 listUser·p0.9999: 23.309 ms/op
                 listUser·p1.00:   24.379 ms/op

Iteration   2: 4.207 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.298 ms/op
                 listUser·p0.50:   4.129 ms/op
                 listUser·p0.90:   4.506 ms/op
                 listUser·p0.95:   4.710 ms/op
                 listUser·p0.99:   7.733 ms/op
                 listUser·p0.999:  15.696 ms/op
                 listUser·p0.9999: 16.777 ms/op
                 listUser·p1.00:   17.564 ms/op

Iteration   3: 4.190 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.343 ms/op
                 listUser·p0.50:   4.104 ms/op
                 listUser·p0.90:   4.669 ms/op
                 listUser·p0.95:   4.923 ms/op
                 listUser·p0.99:   6.767 ms/op
                 listUser·p0.999:  14.287 ms/op
                 listUser·p0.9999: 16.062 ms/op
                 listUser·p1.00:   16.810 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 228978
  mean =      4.189 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 42 
    [ 2.500,  5.000) = 220345 
    [ 5.000,  7.500) = 6718 
    [ 7.500, 10.000) = 1044 
    [10.000, 12.500) = 163 
    [12.500, 15.000) = 391 
    [15.000, 17.500) = 171 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 45 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.303 ms/op
     p(50.0000) =      4.096 ms/op
     p(90.0000) =      4.588 ms/op
     p(95.0000) =      4.833 ms/op
     p(99.0000) =      7.094 ms/op
     p(99.9000) =     15.467 ms/op
     p(99.9900) =     22.813 ms/op
     p(99.9990) =     23.724 ms/op
     p(99.9999) =     24.379 ms/op
    p(100.0000) =     24.379 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.003 ± 0.934  ops/ms
ClientPb.existUser                       thrpt       3   9.620 ± 2.370  ops/ms
ClientPb.getUser                         thrpt       3   9.254 ± 0.248  ops/ms
ClientPb.listUser                        thrpt       3   7.713 ± 2.089  ops/ms
ClientPb.createUser                       avgt       3   3.530 ± 0.896   ms/op
ClientPb.existUser                        avgt       3   3.387 ± 0.908   ms/op
ClientPb.getUser                          avgt       3   3.454 ± 0.322   ms/op
ClientPb.listUser                         avgt       3   4.193 ± 0.781   ms/op
ClientPb.createUser                     sample  271112   3.541 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.022           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.387           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.030           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.407           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.914           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.268           ms/op
ClientPb.createUser:createUser·p0.9999  sample          26.145           ms/op
ClientPb.createUser:createUser·p1.00    sample          31.130           ms/op
ClientPb.existUser                      sample  285700   3.360 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.104           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.219           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.817           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.112           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.693           ms/op
ClientPb.existUser:existUser·p0.999     sample          18.858           ms/op
ClientPb.existUser:existUser·p0.9999    sample          24.670           ms/op
ClientPb.existUser:existUser·p1.00      sample          26.608           ms/op
ClientPb.getUser                        sample  276284   3.472 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.243           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.363           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.863           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.125           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.062           ms/op
ClientPb.getUser:getUser·p0.999         sample          16.843           ms/op
ClientPb.getUser:getUser·p0.9999        sample          23.114           ms/op
ClientPb.getUser:getUser·p1.00          sample          25.231           ms/op
ClientPb.listUser                       sample  228978   4.189 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.303           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.096           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.588           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.833           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.094           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.467           ms/op
ClientPb.listUser:listUser·p0.9999      sample          22.813           ms/op
ClientPb.listUser:listUser·p1.00        sample          24.379           ms/op
