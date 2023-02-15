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
# Warmup Iteration   1: 2.206 ops/ms
# Warmup Iteration   2: 5.935 ops/ms
# Warmup Iteration   3: 7.691 ops/ms
Iteration   1: 9.214 ops/ms
Iteration   2: 9.416 ops/ms
Iteration   3: 9.611 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.414 ±(99.9%) 3.630 ops/ms [Average]
  (min, avg, max) = (9.214, 9.414, 9.611), stdev = 0.199
  CI (99.9%): [5.784, 13.043] (assumes normal distribution)


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
# Warmup Iteration   1: 3.399 ops/ms
# Warmup Iteration   2: 8.883 ops/ms
# Warmup Iteration   3: 9.510 ops/ms
Iteration   1: 9.907 ops/ms
Iteration   2: 9.920 ops/ms
Iteration   3: 10.255 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.027 ±(99.9%) 3.602 ops/ms [Average]
  (min, avg, max) = (9.907, 10.027, 10.255), stdev = 0.197
  CI (99.9%): [6.425, 13.629] (assumes normal distribution)


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
# Warmup Iteration   1: 3.764 ops/ms
# Warmup Iteration   2: 8.896 ops/ms
# Warmup Iteration   3: 9.264 ops/ms
Iteration   1: 9.364 ops/ms
Iteration   2: 9.578 ops/ms
Iteration   3: 9.469 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.470 ±(99.9%) 1.950 ops/ms [Average]
  (min, avg, max) = (9.364, 9.470, 9.578), stdev = 0.107
  CI (99.9%): [7.521, 11.420] (assumes normal distribution)


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
# Warmup Iteration   1: 3.146 ops/ms
# Warmup Iteration   2: 7.667 ops/ms
# Warmup Iteration   3: 8.080 ops/ms
Iteration   1: 8.100 ops/ms
Iteration   2: 8.196 ops/ms
Iteration   3: 8.165 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.154 ±(99.9%) 0.898 ops/ms [Average]
  (min, avg, max) = (8.100, 8.154, 8.196), stdev = 0.049
  CI (99.9%): [7.255, 9.052] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 9.601 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.767 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.481 ±(99.9%) 0.007 ms/op
Iteration   1: 3.377 ±(99.9%) 0.008 ms/op
Iteration   2: 3.325 ±(99.9%) 0.004 ms/op
Iteration   3: 3.235 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.312 ±(99.9%) 1.309 ms/op [Average]
  (min, avg, max) = (3.235, 3.312, 3.377), stdev = 0.072
  CI (99.9%): [2.004, 4.621] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 9.518 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.635 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.391 ±(99.9%) 0.005 ms/op
Iteration   1: 3.295 ±(99.9%) 0.009 ms/op
Iteration   2: 3.167 ±(99.9%) 0.004 ms/op
Iteration   3: 3.167 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.210 ±(99.9%) 1.356 ms/op [Average]
  (min, avg, max) = (3.167, 3.210, 3.295), stdev = 0.074
  CI (99.9%): [1.854, 4.565] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 9.438 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.649 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.467 ±(99.9%) 0.003 ms/op
Iteration   1: 3.342 ±(99.9%) 0.004 ms/op
Iteration   2: 3.306 ±(99.9%) 0.004 ms/op
Iteration   3: 3.336 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.328 ±(99.9%) 0.343 ms/op [Average]
  (min, avg, max) = (3.306, 3.328, 3.342), stdev = 0.019
  CI (99.9%): [2.985, 3.671] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 9.833 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 4.111 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.145 ±(99.9%) 0.005 ms/op
Iteration   1: 3.869 ±(99.9%) 0.012 ms/op
Iteration   2: 3.883 ±(99.9%) 0.011 ms/op
Iteration   3: 4.027 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.926 ±(99.9%) 1.596 ms/op [Average]
  (min, avg, max) = (3.869, 3.926, 4.027), stdev = 0.088
  CI (99.9%): [2.330, 5.523] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 8.825 ±(99.9%) 0.113 ms/op
# Warmup Iteration   2: 3.816 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.312 ±(99.9%) 0.009 ms/op
Iteration   1: 3.267 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.274 ms/op
                 createUser·p0.50:   3.162 ms/op
                 createUser·p0.90:   3.604 ms/op
                 createUser·p0.95:   3.875 ms/op
                 createUser·p0.99:   5.612 ms/op
                 createUser·p0.999:  11.472 ms/op
                 createUser·p0.9999: 23.246 ms/op
                 createUser·p1.00:   24.052 ms/op

Iteration   2: 3.319 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.243 ms/op
                 createUser·p0.50:   3.260 ms/op
                 createUser·p0.90:   3.690 ms/op
                 createUser·p0.95:   4.010 ms/op
                 createUser·p0.99:   5.587 ms/op
                 createUser·p0.999:  21.305 ms/op
                 createUser·p0.9999: 25.669 ms/op
                 createUser·p1.00:   26.935 ms/op

Iteration   3: 3.221 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.456 ms/op
                 createUser·p0.50:   3.133 ms/op
                 createUser·p0.90:   3.518 ms/op
                 createUser·p0.95:   3.740 ms/op
                 createUser·p0.99:   4.784 ms/op
                 createUser·p0.999:  17.138 ms/op
                 createUser·p0.9999: 21.922 ms/op
                 createUser·p1.00:   22.905 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 293667
  mean =      3.269 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10163 
    [ 2.500,  5.000) = 279215 
    [ 5.000,  7.500) = 3431 
    [ 7.500, 10.000) = 439 
    [10.000, 12.500) = 51 
    [12.500, 15.000) = 11 
    [15.000, 17.500) = 65 
    [17.500, 20.000) = 71 
    [20.000, 22.500) = 129 
    [22.500, 25.000) = 71 
    [25.000, 27.500) = 21 

  Percentiles, ms/op:
      p(0.0000) =      1.243 ms/op
     p(50.0000) =      3.178 ms/op
     p(90.0000) =      3.600 ms/op
     p(95.0000) =      3.867 ms/op
     p(99.0000) =      5.505 ms/op
     p(99.9000) =     17.476 ms/op
     p(99.9900) =     24.498 ms/op
     p(99.9990) =     26.653 ms/op
     p(99.9999) =     26.935 ms/op
    p(100.0000) =     26.935 ms/op


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
# Warmup Iteration   1: 7.310 ±(99.9%) 0.087 ms/op
# Warmup Iteration   2: 3.479 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.271 ±(99.9%) 0.008 ms/op
Iteration   1: 3.391 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.511 ms/op
                 existUser·p0.50:   3.285 ms/op
                 existUser·p0.90:   3.867 ms/op
                 existUser·p0.95:   4.211 ms/op
                 existUser·p0.99:   5.816 ms/op
                 existUser·p0.999:  20.872 ms/op
                 existUser·p0.9999: 28.167 ms/op
                 existUser·p1.00:   28.934 ms/op

Iteration   2: 3.241 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.505 ms/op
                 existUser·p0.50:   3.232 ms/op
                 existUser·p0.90:   3.461 ms/op
                 existUser·p0.95:   3.707 ms/op
                 existUser·p0.99:   5.325 ms/op
                 existUser·p0.999:  8.754 ms/op
                 existUser·p0.9999: 28.746 ms/op
                 existUser·p1.00:   29.590 ms/op

Iteration   3: 3.387 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.315 ms/op
                 existUser·p0.50:   3.322 ms/op
                 existUser·p0.90:   3.863 ms/op
                 existUser·p0.95:   4.182 ms/op
                 existUser·p0.99:   5.431 ms/op
                 existUser·p0.999:  18.515 ms/op
                 existUser·p0.9999: 27.056 ms/op
                 existUser·p1.00:   27.820 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 287354
  mean =      3.338 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21207 
    [ 2.500,  5.000) = 260534 
    [ 5.000,  7.500) = 4795 
    [ 7.500, 10.000) = 476 
    [10.000, 12.500) = 72 
    [12.500, 15.000) = 14 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 27 
    [20.000, 22.500) = 76 
    [22.500, 25.000) = 46 
    [25.000, 27.500) = 73 

  Percentiles, ms/op:
      p(0.0000) =      1.315 ms/op
     p(50.0000) =      3.277 ms/op
     p(90.0000) =      3.756 ms/op
     p(95.0000) =      4.092 ms/op
     p(99.0000) =      5.439 ms/op
     p(99.9000) =     12.020 ms/op
     p(99.9900) =     27.853 ms/op
     p(99.9990) =     29.078 ms/op
     p(99.9999) =     29.590 ms/op
    p(100.0000) =     29.590 ms/op


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
# Warmup Iteration   1: 9.168 ±(99.9%) 0.117 ms/op
# Warmup Iteration   2: 3.671 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.434 ±(99.9%) 0.010 ms/op
Iteration   1: 3.391 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.395 ms/op
                 getUser·p0.50:   3.244 ms/op
                 getUser·p0.90:   3.690 ms/op
                 getUser·p0.95:   4.022 ms/op
                 getUser·p0.99:   6.611 ms/op
                 getUser·p0.999:  17.422 ms/op
                 getUser·p0.9999: 20.138 ms/op
                 getUser·p1.00:   20.775 ms/op

Iteration   2: 3.320 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.569 ms/op
                 getUser·p0.50:   3.244 ms/op
                 getUser·p0.90:   3.674 ms/op
                 getUser·p0.95:   3.912 ms/op
                 getUser·p0.99:   5.620 ms/op
                 getUser·p0.999:  16.257 ms/op
                 getUser·p0.9999: 21.729 ms/op
                 getUser·p1.00:   22.348 ms/op

Iteration   3: 3.327 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.346 ms/op
                 getUser·p0.50:   3.211 ms/op
                 getUser·p0.90:   3.621 ms/op
                 getUser·p0.95:   3.797 ms/op
                 getUser·p0.99:   5.947 ms/op
                 getUser·p0.999:  16.102 ms/op
                 getUser·p0.9999: 27.204 ms/op
                 getUser·p1.00:   28.541 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 286626
  mean =      3.346 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4256 
    [ 2.500,  5.000) = 275758 
    [ 5.000,  7.500) = 5421 
    [ 7.500, 10.000) = 799 
    [10.000, 12.500) = 81 
    [12.500, 15.000) = 21 
    [15.000, 17.500) = 27 
    [17.500, 20.000) = 151 
    [20.000, 22.500) = 80 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 25 

  Percentiles, ms/op:
      p(0.0000) =      1.346 ms/op
     p(50.0000) =      3.232 ms/op
     p(90.0000) =      3.658 ms/op
     p(95.0000) =      3.895 ms/op
     p(99.0000) =      6.070 ms/op
     p(99.9000) =     16.576 ms/op
     p(99.9900) =     25.723 ms/op
     p(99.9990) =     28.017 ms/op
     p(99.9999) =     28.541 ms/op
    p(100.0000) =     28.541 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 11.146 ±(99.9%) 0.138 ms/op
# Warmup Iteration   2: 4.389 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.057 ±(99.9%) 0.013 ms/op
Iteration   1: 3.884 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.952 ms/op
                 listUser·p0.50:   3.740 ms/op
                 listUser·p0.90:   4.284 ms/op
                 listUser·p0.95:   4.465 ms/op
                 listUser·p0.99:   6.529 ms/op
                 listUser·p0.999:  17.180 ms/op
                 listUser·p0.9999: 23.128 ms/op
                 listUser·p1.00:   23.953 ms/op

Iteration   2: 3.794 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.015 ms/op
                 listUser·p0.50:   3.756 ms/op
                 listUser·p0.90:   4.010 ms/op
                 listUser·p0.95:   4.227 ms/op
                 listUser·p0.99:   6.406 ms/op
                 listUser·p0.999:  15.789 ms/op
                 listUser·p0.9999: 23.167 ms/op
                 listUser·p1.00:   24.084 ms/op

Iteration   3: 3.866 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.167 ms/op
                 listUser·p0.50:   3.801 ms/op
                 listUser·p0.90:   4.047 ms/op
                 listUser·p0.95:   4.506 ms/op
                 listUser·p0.99:   6.922 ms/op
                 listUser·p0.999:  15.024 ms/op
                 listUser·p0.9999: 18.276 ms/op
                 listUser·p1.00:   18.743 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 249375
  mean =      3.848 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 52 
    [ 2.500,  5.000) = 244165 
    [ 5.000,  7.500) = 3685 
    [ 7.500, 10.000) = 841 
    [10.000, 12.500) = 164 
    [12.500, 15.000) = 177 
    [15.000, 17.500) = 173 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 50 
    [22.500, 25.000) = 36 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.167 ms/op
     p(50.0000) =      3.772 ms/op
     p(90.0000) =      4.162 ms/op
     p(95.0000) =      4.415 ms/op
     p(99.0000) =      6.521 ms/op
     p(99.9000) =     15.544 ms/op
     p(99.9900) =     23.134 ms/op
     p(99.9990) =     24.084 ms/op
     p(99.9999) =     24.084 ms/op
    p(100.0000) =     24.084 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.414 ± 3.630  ops/ms
ClientPb.existUser                       thrpt       3  10.027 ± 3.602  ops/ms
ClientPb.getUser                         thrpt       3   9.470 ± 1.950  ops/ms
ClientPb.listUser                        thrpt       3   8.154 ± 0.898  ops/ms
ClientPb.createUser                       avgt       3   3.312 ± 1.309   ms/op
ClientPb.existUser                        avgt       3   3.210 ± 1.356   ms/op
ClientPb.getUser                          avgt       3   3.328 ± 0.343   ms/op
ClientPb.listUser                         avgt       3   3.926 ± 1.596   ms/op
ClientPb.createUser                     sample  293667   3.269 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.243           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.178           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.600           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.867           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.505           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.476           ms/op
ClientPb.createUser:createUser·p0.9999  sample          24.498           ms/op
ClientPb.createUser:createUser·p1.00    sample          26.935           ms/op
ClientPb.existUser                      sample  287354   3.338 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.315           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.277           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.756           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.092           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.439           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.020           ms/op
ClientPb.existUser:existUser·p0.9999    sample          27.853           ms/op
ClientPb.existUser:existUser·p1.00      sample          29.590           ms/op
ClientPb.getUser                        sample  286626   3.346 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.346           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.232           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.658           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.895           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.070           ms/op
ClientPb.getUser:getUser·p0.999         sample          16.576           ms/op
ClientPb.getUser:getUser·p0.9999        sample          25.723           ms/op
ClientPb.getUser:getUser·p1.00          sample          28.541           ms/op
ClientPb.listUser                       sample  249375   3.848 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.167           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.772           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.162           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.415           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.521           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.544           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.134           ms/op
ClientPb.listUser:listUser·p1.00        sample          24.084           ms/op
