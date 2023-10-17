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
# Warmup Iteration   1: 1.835 ops/ms
# Warmup Iteration   2: 4.716 ops/ms
# Warmup Iteration   3: 7.827 ops/ms
Iteration   1: 8.472 ops/ms
Iteration   2: 8.699 ops/ms
Iteration   3: 8.846 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.672 ±(99.9%) 3.438 ops/ms [Average]
  (min, avg, max) = (8.472, 8.672, 8.846), stdev = 0.188
  CI (99.9%): [5.234, 12.111] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:12
# Fork: 1 of 1
# Warmup Iteration   1: 2.220 ops/ms
# Warmup Iteration   2: 7.411 ops/ms
# Warmup Iteration   3: 8.694 ops/ms
Iteration   1: 9.086 ops/ms
Iteration   2: 9.057 ops/ms
Iteration   3: 9.293 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.146 ±(99.9%) 2.351 ops/ms [Average]
  (min, avg, max) = (9.057, 9.146, 9.293), stdev = 0.129
  CI (99.9%): [6.794, 11.497] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:05
# Fork: 1 of 1
# Warmup Iteration   1: 2.357 ops/ms
# Warmup Iteration   2: 7.213 ops/ms
# Warmup Iteration   3: 8.403 ops/ms
Iteration   1: 8.780 ops/ms
Iteration   2: 8.853 ops/ms
Iteration   3: 8.864 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.832 ±(99.9%) 0.829 ops/ms [Average]
  (min, avg, max) = (8.780, 8.832, 8.864), stdev = 0.045
  CI (99.9%): [8.004, 9.661] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:59
# Fork: 1 of 1
# Warmup Iteration   1: 2.126 ops/ms
# Warmup Iteration   2: 6.324 ops/ms
# Warmup Iteration   3: 7.097 ops/ms
Iteration   1: 7.058 ops/ms
Iteration   2: 7.226 ops/ms
Iteration   3: 7.160 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.148 ±(99.9%) 1.548 ops/ms [Average]
  (min, avg, max) = (7.058, 7.148, 7.226), stdev = 0.085
  CI (99.9%): [5.600, 8.696] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:50
# Fork: 1 of 1
# Warmup Iteration   1: 12.182 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 4.010 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.858 ±(99.9%) 0.004 ms/op
Iteration   1: 3.589 ±(99.9%) 0.006 ms/op
Iteration   2: 3.653 ±(99.9%) 0.006 ms/op
Iteration   3: 3.566 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.603 ±(99.9%) 0.819 ms/op [Average]
  (min, avg, max) = (3.566, 3.603, 3.653), stdev = 0.045
  CI (99.9%): [2.784, 4.422] (assumes normal distribution)


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
# Warmup Iteration   1: 10.180 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 3.837 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.597 ±(99.9%) 0.006 ms/op
Iteration   1: 3.527 ±(99.9%) 0.004 ms/op
Iteration   2: 3.475 ±(99.9%) 0.004 ms/op
Iteration   3: 3.518 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.507 ±(99.9%) 0.505 ms/op [Average]
  (min, avg, max) = (3.475, 3.507, 3.527), stdev = 0.028
  CI (99.9%): [3.002, 4.011] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 10.802 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 4.285 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.821 ±(99.9%) 0.004 ms/op
Iteration   1: 3.732 ±(99.9%) 0.005 ms/op
Iteration   2: 3.775 ±(99.9%) 0.006 ms/op
Iteration   3: 3.667 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.725 ±(99.9%) 0.994 ms/op [Average]
  (min, avg, max) = (3.667, 3.725, 3.775), stdev = 0.054
  CI (99.9%): [2.730, 4.719] (assumes normal distribution)


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
# Warmup Iteration   1: 15.994 ±(99.9%) 0.072 ms/op
# Warmup Iteration   2: 5.426 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.713 ±(99.9%) 0.005 ms/op
Iteration   1: 4.743 ±(99.9%) 0.007 ms/op
Iteration   2: 4.496 ±(99.9%) 0.005 ms/op
Iteration   3: 4.478 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.572 ±(99.9%) 2.697 ms/op [Average]
  (min, avg, max) = (4.478, 4.572, 4.743), stdev = 0.148
  CI (99.9%): [1.875, 7.270] (assumes normal distribution)


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
# Warmup Iteration   1: 12.732 ±(99.9%) 0.188 ms/op
# Warmup Iteration   2: 4.695 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 4.195 ±(99.9%) 0.022 ms/op
Iteration   1: 3.847 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   1.880 ms/op
                 createUser·p0.50:   3.678 ms/op
                 createUser·p0.90:   4.349 ms/op
                 createUser·p0.95:   4.792 ms/op
                 createUser·p0.99:   8.716 ms/op
                 createUser·p0.999:  26.397 ms/op
                 createUser·p0.9999: 43.383 ms/op
                 createUser·p1.00:   44.106 ms/op

Iteration   2: 3.765 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   0.782 ms/op
                 createUser·p0.50:   3.559 ms/op
                 createUser·p0.90:   4.235 ms/op
                 createUser·p0.95:   4.858 ms/op
                 createUser·p0.99:   8.225 ms/op
                 createUser·p0.999:  27.984 ms/op
                 createUser·p0.9999: 31.425 ms/op
                 createUser·p1.00:   32.506 ms/op

Iteration   3: 3.699 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.528 ms/op
                 createUser·p0.50:   3.498 ms/op
                 createUser·p0.90:   4.145 ms/op
                 createUser·p0.95:   4.563 ms/op
                 createUser·p0.99:   8.159 ms/op
                 createUser·p0.999:  29.471 ms/op
                 createUser·p0.9999: 35.805 ms/op
                 createUser·p1.00:   36.831 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 254965
  mean =      3.770 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 244219 
    [ 5.000, 10.000) = 9617 
    [10.000, 15.000) = 732 
    [15.000, 20.000) = 64 
    [20.000, 25.000) = 22 
    [25.000, 30.000) = 152 
    [30.000, 35.000) = 110 
    [35.000, 40.000) = 20 
    [40.000, 45.000) = 29 

  Percentiles, ms/op:
      p(0.0000) =      0.782 ms/op
     p(50.0000) =      3.572 ms/op
     p(90.0000) =      4.243 ms/op
     p(95.0000) =      4.727 ms/op
     p(99.0000) =      8.241 ms/op
     p(99.9000) =     27.626 ms/op
     p(99.9900) =     41.813 ms/op
     p(99.9990) =     44.040 ms/op
     p(99.9999) =     44.106 ms/op
    p(100.0000) =     44.106 ms/op


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
# Warmup Iteration   1: 11.362 ±(99.9%) 0.169 ms/op
# Warmup Iteration   2: 3.920 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.739 ±(99.9%) 0.014 ms/op
Iteration   1: 3.570 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.722 ms/op
                 existUser·p0.50:   3.400 ms/op
                 existUser·p0.90:   4.002 ms/op
                 existUser·p0.95:   4.448 ms/op
                 existUser·p0.99:   7.668 ms/op
                 existUser·p0.999:  11.605 ms/op
                 existUser·p0.9999: 27.136 ms/op
                 existUser·p1.00:   27.918 ms/op

Iteration   2: 3.764 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   1.821 ms/op
                 existUser·p0.50:   3.486 ms/op
                 existUser·p0.90:   4.350 ms/op
                 existUser·p0.95:   5.771 ms/op
                 existUser·p0.99:   8.634 ms/op
                 existUser·p0.999:  14.910 ms/op
                 existUser·p0.9999: 27.591 ms/op
                 existUser·p1.00:   28.213 ms/op

Iteration   3: 3.501 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.370 ms/op
                 existUser·p0.50:   3.375 ms/op
                 existUser·p0.90:   3.842 ms/op
                 existUser·p0.95:   4.202 ms/op
                 existUser·p0.99:   7.165 ms/op
                 existUser·p0.999:  28.055 ms/op
                 existUser·p0.9999: 35.717 ms/op
                 existUser·p1.00:   37.028 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 265845
  mean =      3.609 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4347 
    [ 2.500,  5.000) = 250370 
    [ 5.000,  7.500) = 7327 
    [ 7.500, 10.000) = 2817 
    [10.000, 12.500) = 557 
    [12.500, 15.000) = 162 
    [15.000, 17.500) = 21 
    [17.500, 20.000) = 18 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 44 
    [25.000, 27.500) = 70 
    [27.500, 30.000) = 43 
    [30.000, 32.500) = 35 
    [32.500, 35.000) = 11 
    [35.000, 37.500) = 21 

  Percentiles, ms/op:
      p(0.0000) =      1.370 ms/op
     p(50.0000) =      3.412 ms/op
     p(90.0000) =      4.071 ms/op
     p(95.0000) =      4.628 ms/op
     p(99.0000) =      7.979 ms/op
     p(99.9000) =     14.980 ms/op
     p(99.9900) =     34.357 ms/op
     p(99.9990) =     36.264 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 12.056 ±(99.9%) 0.195 ms/op
# Warmup Iteration   2: 4.243 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 3.830 ±(99.9%) 0.015 ms/op
Iteration   1: 3.911 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   2.091 ms/op
                 getUser·p0.50:   3.510 ms/op
                 getUser·p0.90:   4.694 ms/op
                 getUser·p0.95:   7.102 ms/op
                 getUser·p0.99:   9.585 ms/op
                 getUser·p0.999:  27.034 ms/op
                 getUser·p0.9999: 33.882 ms/op
                 getUser·p1.00:   34.275 ms/op

Iteration   2: 3.770 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   1.753 ms/op
                 getUser·p0.50:   3.514 ms/op
                 getUser·p0.90:   4.276 ms/op
                 getUser·p0.95:   4.932 ms/op
                 getUser·p0.99:   8.569 ms/op
                 getUser·p0.999:  27.275 ms/op
                 getUser·p0.9999: 36.013 ms/op
                 getUser·p1.00:   36.962 ms/op

Iteration   3: 3.692 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.325 ms/op
                 getUser·p0.50:   3.527 ms/op
                 getUser·p0.90:   4.219 ms/op
                 getUser·p0.95:   4.489 ms/op
                 getUser·p0.99:   6.390 ms/op
                 getUser·p0.999:  26.301 ms/op
                 getUser·p0.9999: 38.842 ms/op
                 getUser·p1.00:   40.174 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 253169
  mean =      3.789 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 239617 
    [ 5.000, 10.000) = 12236 
    [10.000, 15.000) = 831 
    [15.000, 20.000) = 196 
    [20.000, 25.000) = 10 
    [25.000, 30.000) = 105 
    [30.000, 35.000) = 118 
    [35.000, 40.000) = 55 
    [40.000, 45.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.325 ms/op
     p(50.0000) =      3.518 ms/op
     p(90.0000) =      4.276 ms/op
     p(95.0000) =      5.202 ms/op
     p(99.0000) =      8.798 ms/op
     p(99.9000) =     26.962 ms/op
     p(99.9900) =     37.400 ms/op
     p(99.9990) =     39.649 ms/op
     p(99.9999) =     40.174 ms/op
    p(100.0000) =     40.174 ms/op


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
# Warmup Iteration   1: 13.544 ±(99.9%) 0.202 ms/op
# Warmup Iteration   2: 5.027 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 4.674 ±(99.9%) 0.019 ms/op
Iteration   1: 4.468 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.939 ms/op
                 listUser·p0.50:   4.211 ms/op
                 listUser·p0.90:   4.981 ms/op
                 listUser·p0.95:   5.579 ms/op
                 listUser·p0.99:   9.355 ms/op
                 listUser·p0.999:  26.326 ms/op
                 listUser·p0.9999: 29.617 ms/op
                 listUser·p1.00:   30.605 ms/op

Iteration   2: 4.562 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   2.091 ms/op
                 listUser·p0.50:   4.350 ms/op
                 listUser·p0.90:   5.087 ms/op
                 listUser·p0.95:   5.710 ms/op
                 listUser·p0.99:   8.897 ms/op
                 listUser·p0.999:  19.071 ms/op
                 listUser·p0.9999: 22.380 ms/op
                 listUser·p1.00:   23.200 ms/op

Iteration   3: 4.486 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.712 ms/op
                 listUser·p0.50:   4.268 ms/op
                 listUser·p0.90:   4.907 ms/op
                 listUser·p0.95:   5.456 ms/op
                 listUser·p0.99:   9.837 ms/op
                 listUser·p0.999:  20.152 ms/op
                 listUser·p0.9999: 21.201 ms/op
                 listUser·p1.00:   21.529 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 212954
  mean =      4.505 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 56 
    [ 2.500,  5.000) = 191259 
    [ 5.000,  7.500) = 16119 
    [ 7.500, 10.000) = 3923 
    [10.000, 12.500) = 804 
    [12.500, 15.000) = 120 
    [15.000, 17.500) = 199 
    [17.500, 20.000) = 187 
    [20.000, 22.500) = 146 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 55 
    [27.500, 30.000) = 51 
    [30.000, 32.500) = 3 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.712 ms/op
     p(50.0000) =      4.268 ms/op
     p(90.0000) =      5.005 ms/op
     p(95.0000) =      5.571 ms/op
     p(99.0000) =      9.437 ms/op
     p(99.9000) =     20.677 ms/op
     p(99.9900) =     28.597 ms/op
     p(99.9990) =     30.134 ms/op
     p(99.9999) =     30.605 ms/op
    p(100.0000) =     30.605 ms/op


# Run complete. Total time: 00:13:15

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.672 ± 3.438  ops/ms
ClientPb.existUser                       thrpt       3   9.146 ± 2.351  ops/ms
ClientPb.getUser                         thrpt       3   8.832 ± 0.829  ops/ms
ClientPb.listUser                        thrpt       3   7.148 ± 1.548  ops/ms
ClientPb.createUser                       avgt       3   3.603 ± 0.819   ms/op
ClientPb.existUser                        avgt       3   3.507 ± 0.505   ms/op
ClientPb.getUser                          avgt       3   3.725 ± 0.994   ms/op
ClientPb.listUser                         avgt       3   4.572 ± 2.697   ms/op
ClientPb.createUser                     sample  254965   3.770 ± 0.009   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.782           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.572           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.243           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.727           ms/op
ClientPb.createUser:createUser·p0.99    sample           8.241           ms/op
ClientPb.createUser:createUser·p0.999   sample          27.626           ms/op
ClientPb.createUser:createUser·p0.9999  sample          41.813           ms/op
ClientPb.createUser:createUser·p1.00    sample          44.106           ms/op
ClientPb.existUser                      sample  265845   3.609 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.370           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.412           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.071           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.628           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.979           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.980           ms/op
ClientPb.existUser:existUser·p0.9999    sample          34.357           ms/op
ClientPb.existUser:existUser·p1.00      sample          37.028           ms/op
ClientPb.getUser                        sample  253169   3.789 ± 0.009   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.325           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.518           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.276           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.202           ms/op
ClientPb.getUser:getUser·p0.99          sample           8.798           ms/op
ClientPb.getUser:getUser·p0.999         sample          26.962           ms/op
ClientPb.getUser:getUser·p0.9999        sample          37.400           ms/op
ClientPb.getUser:getUser·p1.00          sample          40.174           ms/op
ClientPb.listUser                       sample  212954   4.505 ± 0.009   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.712           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.268           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.005           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.571           ms/op
ClientPb.listUser:listUser·p0.99        sample           9.437           ms/op
ClientPb.listUser:listUser·p0.999       sample          20.677           ms/op
ClientPb.listUser:listUser·p0.9999      sample          28.597           ms/op
ClientPb.listUser:listUser·p1.00        sample          30.605           ms/op
