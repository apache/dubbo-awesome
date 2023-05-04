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
# Warmup Iteration   1: 1.249 ops/ms
# Warmup Iteration   2: 3.468 ops/ms
# Warmup Iteration   3: 6.200 ops/ms
Iteration   1: 6.169 ops/ms
Iteration   2: 6.552 ops/ms
Iteration   3: 6.781 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  6.501 ±(99.9%) 5.648 ops/ms [Average]
  (min, avg, max) = (6.169, 6.501, 6.781), stdev = 0.310
  CI (99.9%): [0.853, 12.148] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:11
# Fork: 1 of 1
# Warmup Iteration   1: 1.919 ops/ms
# Warmup Iteration   2: 5.573 ops/ms
# Warmup Iteration   3: 6.703 ops/ms
Iteration   1: 6.875 ops/ms
Iteration   2: 7.004 ops/ms
Iteration   3: 6.657 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.845 ±(99.9%) 3.200 ops/ms [Average]
  (min, avg, max) = (6.657, 6.845, 7.004), stdev = 0.175
  CI (99.9%): [3.645, 10.045] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:04
# Fork: 1 of 1
# Warmup Iteration   1: 1.729 ops/ms
# Warmup Iteration   2: 5.156 ops/ms
# Warmup Iteration   3: 6.455 ops/ms
Iteration   1: 6.278 ops/ms
Iteration   2: 6.324 ops/ms
Iteration   3: 6.577 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  6.393 ±(99.9%) 2.940 ops/ms [Average]
  (min, avg, max) = (6.278, 6.393, 6.577), stdev = 0.161
  CI (99.9%): [3.453, 9.333] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:58
# Fork: 1 of 1
# Warmup Iteration   1: 1.823 ops/ms
# Warmup Iteration   2: 4.490 ops/ms
# Warmup Iteration   3: 5.533 ops/ms
Iteration   1: 5.406 ops/ms
Iteration   2: 5.429 ops/ms
Iteration   3: 5.349 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.395 ±(99.9%) 0.748 ops/ms [Average]
  (min, avg, max) = (5.349, 5.395, 5.429), stdev = 0.041
  CI (99.9%): [4.646, 6.143] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:49
# Fork: 1 of 1
# Warmup Iteration   1: 15.312 ±(99.9%) 0.080 ms/op
# Warmup Iteration   2: 5.895 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 5.212 ±(99.9%) 0.012 ms/op
Iteration   1: 5.021 ±(99.9%) 0.017 ms/op
Iteration   2: 4.703 ±(99.9%) 0.020 ms/op
Iteration   3: 5.046 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.923 ±(99.9%) 3.483 ms/op [Average]
  (min, avg, max) = (4.703, 4.923, 5.046), stdev = 0.191
  CI (99.9%): [1.440, 8.407] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 14.576 ±(99.9%) 0.086 ms/op
# Warmup Iteration   2: 5.433 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.777 ±(99.9%) 0.013 ms/op
Iteration   1: 4.669 ±(99.9%) 0.013 ms/op
Iteration   2: 4.605 ±(99.9%) 0.014 ms/op
Iteration   3: 4.629 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  4.634 ±(99.9%) 0.587 ms/op [Average]
  (min, avg, max) = (4.605, 4.634, 4.669), stdev = 0.032
  CI (99.9%): [4.047, 5.221] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 15.165 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 5.501 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 4.995 ±(99.9%) 0.008 ms/op
Iteration   1: 5.027 ±(99.9%) 0.009 ms/op
Iteration   2: 5.040 ±(99.9%) 0.009 ms/op
Iteration   3: 5.160 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.076 ±(99.9%) 1.345 ms/op [Average]
  (min, avg, max) = (5.027, 5.076, 5.160), stdev = 0.074
  CI (99.9%): [3.731, 6.420] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 16.353 ±(99.9%) 0.075 ms/op
# Warmup Iteration   2: 6.519 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 5.555 ±(99.9%) 0.010 ms/op
Iteration   1: 5.883 ±(99.9%) 0.017 ms/op
Iteration   2: 6.423 ±(99.9%) 0.014 ms/op
Iteration   3: 6.376 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.227 ±(99.9%) 5.457 ms/op [Average]
  (min, avg, max) = (5.883, 6.227, 6.423), stdev = 0.299
  CI (99.9%): [0.770, 11.684] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 16.145 ±(99.9%) 0.253 ms/op
# Warmup Iteration   2: 5.889 ±(99.9%) 0.030 ms/op
# Warmup Iteration   3: 5.537 ±(99.9%) 0.023 ms/op
Iteration   1: 5.054 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   1.874 ms/op
                 createUser·p0.50:   4.768 ms/op
                 createUser·p0.90:   6.226 ms/op
                 createUser·p0.95:   7.217 ms/op
                 createUser·p0.99:   10.262 ms/op
                 createUser·p0.999:  21.892 ms/op
                 createUser·p0.9999: 27.538 ms/op
                 createUser·p1.00:   28.312 ms/op

Iteration   2: 5.108 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   1.901 ms/op
                 createUser·p0.50:   4.850 ms/op
                 createUser·p0.90:   6.259 ms/op
                 createUser·p0.95:   7.012 ms/op
                 createUser·p0.99:   10.289 ms/op
                 createUser·p0.999:  27.787 ms/op
                 createUser·p0.9999: 31.461 ms/op
                 createUser·p1.00:   32.178 ms/op

Iteration   3: 4.938 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   2.134 ms/op
                 createUser·p0.50:   4.751 ms/op
                 createUser·p0.90:   5.898 ms/op
                 createUser·p0.95:   6.496 ms/op
                 createUser·p0.99:   8.815 ms/op
                 createUser·p0.999:  23.500 ms/op
                 createUser·p0.9999: 28.741 ms/op
                 createUser·p1.00:   29.753 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 190662
  mean =      5.032 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 51 
    [ 2.500,  5.000) = 115997 
    [ 5.000,  7.500) = 68385 
    [ 7.500, 10.000) = 4412 
    [10.000, 12.500) = 1031 
    [12.500, 15.000) = 456 
    [15.000, 17.500) = 76 
    [17.500, 20.000) = 6 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 35 
    [25.000, 27.500) = 93 
    [27.500, 30.000) = 86 
    [30.000, 32.500) = 8 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.874 ms/op
     p(50.0000) =      4.784 ms/op
     p(90.0000) =      6.128 ms/op
     p(95.0000) =      6.930 ms/op
     p(99.0000) =      9.880 ms/op
     p(99.9000) =     24.882 ms/op
     p(99.9900) =     29.489 ms/op
     p(99.9990) =     32.119 ms/op
     p(99.9999) =     32.178 ms/op
    p(100.0000) =     32.178 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 15.796 ±(99.9%) 0.215 ms/op
# Warmup Iteration   2: 5.863 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 5.156 ±(99.9%) 0.019 ms/op
Iteration   1: 5.048 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   1.929 ms/op
                 existUser·p0.50:   4.743 ms/op
                 existUser·p0.90:   6.300 ms/op
                 existUser·p0.95:   7.234 ms/op
                 existUser·p0.99:   9.798 ms/op
                 existUser·p0.999:  21.328 ms/op
                 existUser·p0.9999: 27.055 ms/op
                 existUser·p1.00:   27.525 ms/op

Iteration   2: 4.948 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   2.028 ms/op
                 existUser·p0.50:   4.637 ms/op
                 existUser·p0.90:   6.152 ms/op
                 existUser·p0.95:   7.176 ms/op
                 existUser·p0.99:   10.404 ms/op
                 existUser·p0.999:  21.922 ms/op
                 existUser·p0.9999: 27.394 ms/op
                 existUser·p1.00:   28.508 ms/op

Iteration   3: 4.759 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   0.446 ms/op
                 existUser·p0.50:   4.522 ms/op
                 existUser·p0.90:   5.923 ms/op
                 existUser·p0.95:   6.570 ms/op
                 existUser·p0.99:   8.380 ms/op
                 existUser·p0.999:  15.461 ms/op
                 existUser·p0.9999: 32.581 ms/op
                 existUser·p1.00:   33.358 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 195183
  mean =      4.916 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 59 
    [ 2.500,  5.000) = 131947 
    [ 5.000,  7.500) = 56733 
    [ 7.500, 10.000) = 4799 
    [10.000, 12.500) = 928 
    [12.500, 15.000) = 404 
    [15.000, 17.500) = 105 
    [17.500, 20.000) = 12 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 53 
    [25.000, 27.500) = 49 
    [27.500, 30.000) = 31 
    [30.000, 32.500) = 31 
    [32.500, 35.000) = 8 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.446 ms/op
     p(50.0000) =      4.628 ms/op
     p(90.0000) =      6.136 ms/op
     p(95.0000) =      6.963 ms/op
     p(99.0000) =      9.601 ms/op
     p(99.9000) =     21.382 ms/op
     p(99.9900) =     31.178 ms/op
     p(99.9990) =     32.984 ms/op
     p(99.9999) =     33.358 ms/op
    p(100.0000) =     33.358 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 14.897 ±(99.9%) 0.223 ms/op
# Warmup Iteration   2: 5.701 ±(99.9%) 0.032 ms/op
# Warmup Iteration   3: 5.105 ±(99.9%) 0.019 ms/op
Iteration   1: 5.220 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   2.077 ms/op
                 getUser·p0.50:   4.858 ms/op
                 getUser·p0.90:   6.545 ms/op
                 getUser·p0.95:   7.807 ms/op
                 getUser·p0.99:   10.839 ms/op
                 getUser·p0.999:  21.037 ms/op
                 getUser·p0.9999: 24.178 ms/op
                 getUser·p1.00:   24.740 ms/op

Iteration   2: 4.951 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   2.105 ms/op
                 getUser·p0.50:   4.702 ms/op
                 getUser·p0.90:   6.038 ms/op
                 getUser·p0.95:   6.726 ms/op
                 getUser·p0.99:   9.175 ms/op
                 getUser·p0.999:  21.095 ms/op
                 getUser·p0.9999: 31.868 ms/op
                 getUser·p1.00:   33.194 ms/op

Iteration   3: 4.927 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   2.384 ms/op
                 getUser·p0.50:   4.678 ms/op
                 getUser·p0.90:   5.939 ms/op
                 getUser·p0.95:   6.717 ms/op
                 getUser·p0.99:   9.241 ms/op
                 getUser·p0.999:  18.336 ms/op
                 getUser·p0.9999: 29.672 ms/op
                 getUser·p1.00:   30.704 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 191034
  mean =      5.029 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6 
    [ 2.500,  5.000) = 120604 
    [ 5.000,  7.500) = 63039 
    [ 7.500, 10.000) = 5590 
    [10.000, 12.500) = 1260 
    [12.500, 15.000) = 265 
    [15.000, 17.500) = 35 
    [17.500, 20.000) = 26 
    [20.000, 22.500) = 41 
    [22.500, 25.000) = 50 
    [25.000, 27.500) = 44 
    [27.500, 30.000) = 43 
    [30.000, 32.500) = 28 
    [32.500, 35.000) = 3 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.077 ms/op
     p(50.0000) =      4.743 ms/op
     p(90.0000) =      6.169 ms/op
     p(95.0000) =      7.078 ms/op
     p(99.0000) =      9.863 ms/op
     p(99.9000) =     21.002 ms/op
     p(99.9900) =     30.933 ms/op
     p(99.9990) =     32.806 ms/op
     p(99.9999) =     33.194 ms/op
    p(100.0000) =     33.194 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 17.075 ±(99.9%) 0.296 ms/op
# Warmup Iteration   2: 6.631 ±(99.9%) 0.037 ms/op
# Warmup Iteration   3: 6.051 ±(99.9%) 0.026 ms/op
Iteration   1: 5.609 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   2.040 ms/op
                 listUser·p0.50:   5.243 ms/op
                 listUser·p0.90:   6.947 ms/op
                 listUser·p0.95:   8.069 ms/op
                 listUser·p0.99:   11.158 ms/op
                 listUser·p0.999:  25.297 ms/op
                 listUser·p0.9999: 28.321 ms/op
                 listUser·p1.00:   29.426 ms/op

Iteration   2: 5.589 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   0.518 ms/op
                 listUser·p0.50:   5.226 ms/op
                 listUser·p0.90:   6.816 ms/op
                 listUser·p0.95:   7.758 ms/op
                 listUser·p0.99:   10.306 ms/op
                 listUser·p0.999:  28.901 ms/op
                 listUser·p0.9999: 33.900 ms/op
                 listUser·p1.00:   44.433 ms/op

Iteration   3: 5.687 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   2.605 ms/op
                 listUser·p0.50:   5.366 ms/op
                 listUser·p0.90:   6.930 ms/op
                 listUser·p0.95:   7.889 ms/op
                 listUser·p0.99:   10.633 ms/op
                 listUser·p0.999:  21.201 ms/op
                 listUser·p0.9999: 25.932 ms/op
                 listUser·p1.00:   26.804 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 170693
  mean =      5.628 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 53450 
    [ 5.000, 10.000) = 114945 
    [10.000, 15.000) = 1818 
    [15.000, 20.000) = 177 
    [20.000, 25.000) = 120 
    [25.000, 30.000) = 147 
    [30.000, 35.000) = 35 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.518 ms/op
     p(50.0000) =      5.276 ms/op
     p(90.0000) =      6.889 ms/op
     p(95.0000) =      7.913 ms/op
     p(99.0000) =     10.830 ms/op
     p(99.9000) =     25.405 ms/op
     p(99.9900) =     32.794 ms/op
     p(99.9990) =     37.484 ms/op
     p(99.9999) =     44.433 ms/op
    p(100.0000) =     44.433 ms/op


# Run complete. Total time: 00:13:16

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   6.501 ± 5.648  ops/ms
ClientPb.existUser                       thrpt       3   6.845 ± 3.200  ops/ms
ClientPb.getUser                         thrpt       3   6.393 ± 2.940  ops/ms
ClientPb.listUser                        thrpt       3   5.395 ± 0.748  ops/ms
ClientPb.createUser                       avgt       3   4.923 ± 3.483   ms/op
ClientPb.existUser                        avgt       3   4.634 ± 0.587   ms/op
ClientPb.getUser                          avgt       3   5.076 ± 1.345   ms/op
ClientPb.listUser                         avgt       3   6.227 ± 5.457   ms/op
ClientPb.createUser                     sample  190662   5.032 ± 0.010   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.874           ms/op
ClientPb.createUser:createUser·p0.50    sample           4.784           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.128           ms/op
ClientPb.createUser:createUser·p0.95    sample           6.930           ms/op
ClientPb.createUser:createUser·p0.99    sample           9.880           ms/op
ClientPb.createUser:createUser·p0.999   sample          24.882           ms/op
ClientPb.createUser:createUser·p0.9999  sample          29.489           ms/op
ClientPb.createUser:createUser·p1.00    sample          32.178           ms/op
ClientPb.existUser                      sample  195183   4.916 ± 0.010   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.446           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.628           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.136           ms/op
ClientPb.existUser:existUser·p0.95      sample           6.963           ms/op
ClientPb.existUser:existUser·p0.99      sample           9.601           ms/op
ClientPb.existUser:existUser·p0.999     sample          21.382           ms/op
ClientPb.existUser:existUser·p0.9999    sample          31.178           ms/op
ClientPb.existUser:existUser·p1.00      sample          33.358           ms/op
ClientPb.getUser                        sample  191034   5.029 ± 0.010   ms/op
ClientPb.getUser:getUser·p0.00          sample           2.077           ms/op
ClientPb.getUser:getUser·p0.50          sample           4.743           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.169           ms/op
ClientPb.getUser:getUser·p0.95          sample           7.078           ms/op
ClientPb.getUser:getUser·p0.99          sample           9.863           ms/op
ClientPb.getUser:getUser·p0.999         sample          21.002           ms/op
ClientPb.getUser:getUser·p0.9999        sample          30.933           ms/op
ClientPb.getUser:getUser·p1.00          sample          33.194           ms/op
ClientPb.listUser                       sample  170693   5.628 ± 0.012   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.518           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.276           ms/op
ClientPb.listUser:listUser·p0.90        sample           6.889           ms/op
ClientPb.listUser:listUser·p0.95        sample           7.913           ms/op
ClientPb.listUser:listUser·p0.99        sample          10.830           ms/op
ClientPb.listUser:listUser·p0.999       sample          25.405           ms/op
ClientPb.listUser:listUser·p0.9999      sample          32.794           ms/op
ClientPb.listUser:listUser·p1.00        sample          44.433           ms/op
