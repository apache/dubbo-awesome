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
# Warmup Iteration   1: 2.080 ops/ms
# Warmup Iteration   2: 5.575 ops/ms
# Warmup Iteration   3: 8.983 ops/ms
Iteration   1: 9.231 ops/ms
Iteration   2: 9.693 ops/ms
Iteration   3: 9.543 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.489 ±(99.9%) 4.299 ops/ms [Average]
  (min, avg, max) = (9.231, 9.489, 9.693), stdev = 0.236
  CI (99.9%): [5.190, 13.789] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 3.048 ops/ms
# Warmup Iteration   2: 9.027 ops/ms
# Warmup Iteration   3: 9.446 ops/ms
Iteration   1: 9.889 ops/ms
Iteration   2: 9.785 ops/ms
Iteration   3: 9.674 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.783 ±(99.9%) 1.964 ops/ms [Average]
  (min, avg, max) = (9.674, 9.783, 9.889), stdev = 0.108
  CI (99.9%): [7.819, 11.747] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 2.662 ops/ms
# Warmup Iteration   2: 8.190 ops/ms
# Warmup Iteration   3: 9.081 ops/ms
Iteration   1: 9.249 ops/ms
Iteration   2: 9.673 ops/ms
Iteration   3: 9.415 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.446 ±(99.9%) 3.902 ops/ms [Average]
  (min, avg, max) = (9.249, 9.446, 9.673), stdev = 0.214
  CI (99.9%): [5.543, 13.348] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 2.847 ops/ms
# Warmup Iteration   2: 7.418 ops/ms
# Warmup Iteration   3: 7.848 ops/ms
Iteration   1: 7.984 ops/ms
Iteration   2: 8.147 ops/ms
Iteration   3: 7.993 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.042 ±(99.9%) 1.674 ops/ms [Average]
  (min, avg, max) = (7.984, 8.042, 8.147), stdev = 0.092
  CI (99.9%): [6.367, 9.716] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 9.299 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.681 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.407 ±(99.9%) 0.011 ms/op
Iteration   1: 3.401 ±(99.9%) 0.006 ms/op
Iteration   2: 3.633 ±(99.9%) 0.006 ms/op
Iteration   3: 3.237 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.424 ±(99.9%) 3.629 ms/op [Average]
  (min, avg, max) = (3.237, 3.424, 3.633), stdev = 0.199
  CI (99.9%): [≈ 0, 7.053] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 7.771 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.650 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.401 ±(99.9%) 0.002 ms/op
Iteration   1: 3.320 ±(99.9%) 0.009 ms/op
Iteration   2: 3.294 ±(99.9%) 0.002 ms/op
Iteration   3: 3.237 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.284 ±(99.9%) 0.771 ms/op [Average]
  (min, avg, max) = (3.237, 3.284, 3.320), stdev = 0.042
  CI (99.9%): [2.512, 4.055] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 10.377 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.977 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.614 ±(99.9%) 0.006 ms/op
Iteration   1: 3.386 ±(99.9%) 0.005 ms/op
Iteration   2: 3.374 ±(99.9%) 0.005 ms/op
Iteration   3: 3.330 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.364 ±(99.9%) 0.535 ms/op [Average]
  (min, avg, max) = (3.330, 3.364, 3.386), stdev = 0.029
  CI (99.9%): [2.828, 3.899] (assumes normal distribution)


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
# Warmup Iteration   1: 10.681 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 4.227 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.959 ±(99.9%) 0.009 ms/op
Iteration   1: 3.924 ±(99.9%) 0.013 ms/op
Iteration   2: 3.875 ±(99.9%) 0.012 ms/op
Iteration   3: 3.869 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.889 ±(99.9%) 0.550 ms/op [Average]
  (min, avg, max) = (3.869, 3.889, 3.924), stdev = 0.030
  CI (99.9%): [3.340, 4.439] (assumes normal distribution)


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
# Warmup Iteration   1: 10.652 ±(99.9%) 0.114 ms/op
# Warmup Iteration   2: 4.137 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 3.570 ±(99.9%) 0.013 ms/op
Iteration   1: 3.383 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.622 ms/op
                 createUser·p0.50:   3.273 ms/op
                 createUser·p0.90:   3.822 ms/op
                 createUser·p0.95:   4.227 ms/op
                 createUser·p0.99:   6.193 ms/op
                 createUser·p0.999:  19.119 ms/op
                 createUser·p0.9999: 23.626 ms/op
                 createUser·p1.00:   24.904 ms/op

Iteration   2: 3.358 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.526 ms/op
                 createUser·p0.50:   3.187 ms/op
                 createUser·p0.90:   3.805 ms/op
                 createUser·p0.95:   4.121 ms/op
                 createUser·p0.99:   6.440 ms/op
                 createUser·p0.999:  21.380 ms/op
                 createUser·p0.9999: 24.133 ms/op
                 createUser·p1.00:   25.362 ms/op

Iteration   3: 3.403 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.331 ms/op
                 createUser·p0.50:   3.269 ms/op
                 createUser·p0.90:   3.871 ms/op
                 createUser·p0.95:   4.112 ms/op
                 createUser·p0.99:   5.267 ms/op
                 createUser·p0.999:  16.320 ms/op
                 createUser·p0.9999: 23.737 ms/op
                 createUser·p1.00:   25.035 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 283665
  mean =      3.381 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5879 
    [ 2.500,  5.000) = 271410 
    [ 5.000,  7.500) = 5076 
    [ 7.500, 10.000) = 723 
    [10.000, 12.500) = 165 
    [12.500, 15.000) = 95 
    [15.000, 17.500) = 46 
    [17.500, 20.000) = 44 
    [20.000, 22.500) = 130 
    [22.500, 25.000) = 91 
    [25.000, 27.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      1.331 ms/op
     p(50.0000) =      3.244 ms/op
     p(90.0000) =      3.838 ms/op
     p(95.0000) =      4.145 ms/op
     p(99.0000) =      6.103 ms/op
     p(99.9000) =     16.455 ms/op
     p(99.9900) =     23.810 ms/op
     p(99.9990) =     25.187 ms/op
     p(99.9999) =     25.362 ms/op
    p(100.0000) =     25.362 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 10.819 ±(99.9%) 0.115 ms/op
# Warmup Iteration   2: 3.664 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.334 ±(99.9%) 0.009 ms/op
Iteration   1: 3.264 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.241 ms/op
                 existUser·p0.50:   3.133 ms/op
                 existUser·p0.90:   3.584 ms/op
                 existUser·p0.95:   3.887 ms/op
                 existUser·p0.99:   5.857 ms/op
                 existUser·p0.999:  9.711 ms/op
                 existUser·p0.9999: 19.837 ms/op
                 existUser·p1.00:   20.742 ms/op

Iteration   2: 3.304 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.013 ms/op
                 existUser·p0.50:   3.232 ms/op
                 existUser·p0.90:   3.531 ms/op
                 existUser·p0.95:   3.961 ms/op
                 existUser·p0.99:   6.447 ms/op
                 existUser·p0.999:  16.052 ms/op
                 existUser·p0.9999: 25.229 ms/op
                 existUser·p1.00:   25.887 ms/op

Iteration   3: 3.294 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.463 ms/op
                 existUser·p0.50:   3.277 ms/op
                 existUser·p0.90:   3.478 ms/op
                 existUser·p0.95:   3.895 ms/op
                 existUser·p0.99:   6.085 ms/op
                 existUser·p0.999:  13.763 ms/op
                 existUser·p0.9999: 23.555 ms/op
                 existUser·p1.00:   24.216 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 292151
  mean =      3.287 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16890 
    [ 2.500,  5.000) = 268474 
    [ 5.000,  7.500) = 5678 
    [ 7.500, 10.000) = 647 
    [10.000, 12.500) = 100 
    [12.500, 15.000) = 69 
    [15.000, 17.500) = 12 
    [17.500, 20.000) = 152 
    [20.000, 22.500) = 67 
    [22.500, 25.000) = 50 
    [25.000, 27.500) = 12 

  Percentiles, ms/op:
      p(0.0000) =      0.463 ms/op
     p(50.0000) =      3.219 ms/op
     p(90.0000) =      3.539 ms/op
     p(95.0000) =      3.912 ms/op
     p(99.0000) =      6.087 ms/op
     p(99.9000) =     15.121 ms/op
     p(99.9900) =     23.881 ms/op
     p(99.9990) =     25.403 ms/op
     p(99.9999) =     25.887 ms/op
    p(100.0000) =     25.887 ms/op


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
# Warmup Iteration   1: 9.250 ±(99.9%) 0.119 ms/op
# Warmup Iteration   2: 3.676 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.440 ±(99.9%) 0.010 ms/op
Iteration   1: 3.459 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.632 ms/op
                 getUser·p0.50:   3.297 ms/op
                 getUser·p0.90:   3.752 ms/op
                 getUser·p0.95:   4.125 ms/op
                 getUser·p0.99:   6.575 ms/op
                 getUser·p0.999:  19.333 ms/op
                 getUser·p0.9999: 27.517 ms/op
                 getUser·p1.00:   28.705 ms/op

Iteration   2: 3.563 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.651 ms/op
                 getUser·p0.50:   3.441 ms/op
                 getUser·p0.90:   4.157 ms/op
                 getUser·p0.95:   4.456 ms/op
                 getUser·p0.99:   5.841 ms/op
                 getUser·p0.999:  23.307 ms/op
                 getUser·p0.9999: 28.480 ms/op
                 getUser·p1.00:   30.081 ms/op

Iteration   3: 3.378 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.331 ms/op
                 getUser·p0.50:   3.256 ms/op
                 getUser·p0.90:   3.695 ms/op
                 getUser·p0.95:   3.949 ms/op
                 getUser·p0.99:   6.463 ms/op
                 getUser·p0.999:  15.756 ms/op
                 getUser·p0.9999: 24.495 ms/op
                 getUser·p1.00:   24.969 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 276830
  mean =      3.465 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5634 
    [ 2.500,  5.000) = 263835 
    [ 5.000,  7.500) = 6303 
    [ 7.500, 10.000) = 518 
    [10.000, 12.500) = 175 
    [12.500, 15.000) = 13 
    [15.000, 17.500) = 74 
    [17.500, 20.000) = 45 
    [20.000, 22.500) = 68 
    [22.500, 25.000) = 79 
    [25.000, 27.500) = 65 
    [27.500, 30.000) = 20 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.331 ms/op
     p(50.0000) =      3.338 ms/op
     p(90.0000) =      3.928 ms/op
     p(95.0000) =      4.268 ms/op
     p(99.0000) =      6.210 ms/op
     p(99.9000) =     17.750 ms/op
     p(99.9900) =     27.427 ms/op
     p(99.9990) =     29.040 ms/op
     p(99.9999) =     30.081 ms/op
    p(100.0000) =     30.081 ms/op


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
# Warmup Iteration   1: 11.743 ±(99.9%) 0.156 ms/op
# Warmup Iteration   2: 4.426 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.108 ±(99.9%) 0.013 ms/op
Iteration   1: 3.965 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.991 ms/op
                 listUser·p0.50:   3.858 ms/op
                 listUser·p0.90:   4.235 ms/op
                 listUser·p0.95:   4.497 ms/op
                 listUser·p0.99:   7.234 ms/op
                 listUser·p0.999:  19.399 ms/op
                 listUser·p0.9999: 23.553 ms/op
                 listUser·p1.00:   24.216 ms/op

Iteration   2: 3.920 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.298 ms/op
                 listUser·p0.50:   3.854 ms/op
                 listUser·p0.90:   4.141 ms/op
                 listUser·p0.95:   4.391 ms/op
                 listUser·p0.99:   7.037 ms/op
                 listUser·p0.999:  14.516 ms/op
                 listUser·p0.9999: 16.581 ms/op
                 listUser·p1.00:   16.679 ms/op

Iteration   3: 4.033 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.515 ms/op
                 listUser·p0.50:   3.879 ms/op
                 listUser·p0.90:   4.440 ms/op
                 listUser·p0.95:   4.956 ms/op
                 listUser·p0.99:   7.382 ms/op
                 listUser·p0.999:  14.912 ms/op
                 listUser·p0.9999: 17.203 ms/op
                 listUser·p1.00:   17.465 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 241636
  mean =      3.972 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22 
    [ 2.500,  5.000) = 233195 
    [ 5.000,  7.500) = 6324 
    [ 7.500, 10.000) = 1252 
    [10.000, 12.500) = 355 
    [12.500, 15.000) = 233 
    [15.000, 17.500) = 127 
    [17.500, 20.000) = 69 
    [20.000, 22.500) = 36 
    [22.500, 25.000) = 23 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.991 ms/op
     p(50.0000) =      3.863 ms/op
     p(90.0000) =      4.276 ms/op
     p(95.0000) =      4.596 ms/op
     p(99.0000) =      7.181 ms/op
     p(99.9000) =     15.041 ms/op
     p(99.9900) =     22.463 ms/op
     p(99.9990) =     24.084 ms/op
     p(99.9999) =     24.216 ms/op
    p(100.0000) =     24.216 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.489 ± 4.299  ops/ms
ClientPb.existUser                       thrpt       3   9.783 ± 1.964  ops/ms
ClientPb.getUser                         thrpt       3   9.446 ± 3.902  ops/ms
ClientPb.listUser                        thrpt       3   8.042 ± 1.674  ops/ms
ClientPb.createUser                       avgt       3   3.424 ± 3.629   ms/op
ClientPb.existUser                        avgt       3   3.284 ± 0.771   ms/op
ClientPb.getUser                          avgt       3   3.364 ± 0.535   ms/op
ClientPb.listUser                         avgt       3   3.889 ± 0.550   ms/op
ClientPb.createUser                     sample  283665   3.381 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.331           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.244           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.838           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.145           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.103           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.455           ms/op
ClientPb.createUser:createUser·p0.9999  sample          23.810           ms/op
ClientPb.createUser:createUser·p1.00    sample          25.362           ms/op
ClientPb.existUser                      sample  292151   3.287 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.463           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.219           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.539           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.912           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.087           ms/op
ClientPb.existUser:existUser·p0.999     sample          15.121           ms/op
ClientPb.existUser:existUser·p0.9999    sample          23.881           ms/op
ClientPb.existUser:existUser·p1.00      sample          25.887           ms/op
ClientPb.getUser                        sample  276830   3.465 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.331           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.338           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.928           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.268           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.210           ms/op
ClientPb.getUser:getUser·p0.999         sample          17.750           ms/op
ClientPb.getUser:getUser·p0.9999        sample          27.427           ms/op
ClientPb.getUser:getUser·p1.00          sample          30.081           ms/op
ClientPb.listUser                       sample  241636   3.972 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.991           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.863           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.276           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.596           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.181           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.041           ms/op
ClientPb.listUser:listUser·p0.9999      sample          22.463           ms/op
ClientPb.listUser:listUser·p1.00        sample          24.216           ms/op
