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
# Warmup Iteration   1: 1.534 ops/ms
# Warmup Iteration   2: 3.669 ops/ms
# Warmup Iteration   3: 7.353 ops/ms
Iteration   1: 7.182 ops/ms
Iteration   2: 7.755 ops/ms
Iteration   3: 7.971 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.636 ±(99.9%) 7.434 ops/ms [Average]
  (min, avg, max) = (7.182, 7.636, 7.971), stdev = 0.407
  CI (99.9%): [0.202, 15.071] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:11
# Fork: 1 of 1
# Warmup Iteration   1: 2.294 ops/ms
# Warmup Iteration   2: 7.330 ops/ms
# Warmup Iteration   3: 8.045 ops/ms
Iteration   1: 8.347 ops/ms
Iteration   2: 8.165 ops/ms
Iteration   3: 8.062 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.191 ±(99.9%) 2.631 ops/ms [Average]
  (min, avg, max) = (8.062, 8.191, 8.347), stdev = 0.144
  CI (99.9%): [5.560, 10.823] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:04
# Fork: 1 of 1
# Warmup Iteration   1: 2.226 ops/ms
# Warmup Iteration   2: 6.208 ops/ms
# Warmup Iteration   3: 7.376 ops/ms
Iteration   1: 7.965 ops/ms
Iteration   2: 8.119 ops/ms
Iteration   3: 8.047 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.043 ±(99.9%) 1.409 ops/ms [Average]
  (min, avg, max) = (7.965, 8.043, 8.119), stdev = 0.077
  CI (99.9%): [6.635, 9.452] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:58
# Fork: 1 of 1
# Warmup Iteration   1: 2.030 ops/ms
# Warmup Iteration   2: 5.649 ops/ms
# Warmup Iteration   3: 6.404 ops/ms
Iteration   1: 6.573 ops/ms
Iteration   2: 6.902 ops/ms
Iteration   3: 6.755 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.744 ±(99.9%) 3.004 ops/ms [Average]
  (min, avg, max) = (6.573, 6.744, 6.902), stdev = 0.165
  CI (99.9%): [3.739, 9.748] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:51
# Fork: 1 of 1
# Warmup Iteration   1: 12.747 ±(99.9%) 0.066 ms/op
# Warmup Iteration   2: 4.508 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.161 ±(99.9%) 0.011 ms/op
Iteration   1: 4.001 ±(99.9%) 0.009 ms/op
Iteration   2: 4.039 ±(99.9%) 0.010 ms/op
Iteration   3: 4.022 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.021 ±(99.9%) 0.354 ms/op [Average]
  (min, avg, max) = (4.001, 4.021, 4.039), stdev = 0.019
  CI (99.9%): [3.667, 4.374] (assumes normal distribution)


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
# Warmup Iteration   1: 12.482 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 4.529 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.033 ±(99.9%) 0.005 ms/op
Iteration   1: 4.104 ±(99.9%) 0.003 ms/op
Iteration   2: 4.160 ±(99.9%) 0.008 ms/op
Iteration   3: 4.152 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  4.139 ±(99.9%) 0.554 ms/op [Average]
  (min, avg, max) = (4.104, 4.139, 4.160), stdev = 0.030
  CI (99.9%): [3.584, 4.693] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:37
# Fork: 1 of 1
# Warmup Iteration   1: 13.302 ±(99.9%) 0.079 ms/op
# Warmup Iteration   2: 5.021 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.415 ±(99.9%) 0.004 ms/op
Iteration   1: 4.258 ±(99.9%) 0.004 ms/op
Iteration   2: 4.256 ±(99.9%) 0.012 ms/op
Iteration   3: 4.075 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.197 ±(99.9%) 1.914 ms/op [Average]
  (min, avg, max) = (4.075, 4.197, 4.258), stdev = 0.105
  CI (99.9%): [2.283, 6.110] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:31
# Fork: 1 of 1
# Warmup Iteration   1: 15.796 ±(99.9%) 0.075 ms/op
# Warmup Iteration   2: 5.956 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.952 ±(99.9%) 0.007 ms/op
Iteration   1: 4.888 ±(99.9%) 0.006 ms/op
Iteration   2: 4.932 ±(99.9%) 0.006 ms/op
Iteration   3: 4.695 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.838 ±(99.9%) 2.304 ms/op [Average]
  (min, avg, max) = (4.695, 4.838, 4.932), stdev = 0.126
  CI (99.9%): [2.534, 7.143] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 13.584 ±(99.9%) 0.196 ms/op
# Warmup Iteration   2: 4.979 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 4.347 ±(99.9%) 0.018 ms/op
Iteration   1: 4.070 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.778 ms/op
                 createUser·p0.50:   3.858 ms/op
                 createUser·p0.90:   4.751 ms/op
                 createUser·p0.95:   5.489 ms/op
                 createUser·p0.99:   8.061 ms/op
                 createUser·p0.999:  15.404 ms/op
                 createUser·p0.9999: 30.410 ms/op
                 createUser·p1.00:   33.817 ms/op

Iteration   2: 3.938 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.999 ms/op
                 createUser·p0.50:   3.781 ms/op
                 createUser·p0.90:   4.481 ms/op
                 createUser·p0.95:   4.948 ms/op
                 createUser·p0.99:   7.447 ms/op
                 createUser·p0.999:  26.235 ms/op
                 createUser·p0.9999: 34.865 ms/op
                 createUser·p1.00:   35.389 ms/op

Iteration   3: 4.078 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   2.015 ms/op
                 createUser·p0.50:   3.908 ms/op
                 createUser·p0.90:   4.735 ms/op
                 createUser·p0.95:   5.153 ms/op
                 createUser·p0.99:   7.348 ms/op
                 createUser·p0.999:  33.714 ms/op
                 createUser·p0.9999: 44.639 ms/op
                 createUser·p1.00:   45.220 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 238455
  mean =      4.028 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 224119 
    [ 5.000, 10.000) = 13546 
    [10.000, 15.000) = 487 
    [15.000, 20.000) = 44 
    [20.000, 25.000) = 7 
    [25.000, 30.000) = 119 
    [30.000, 35.000) = 72 
    [35.000, 40.000) = 29 
    [40.000, 45.000) = 31 

  Percentiles, ms/op:
      p(0.0000) =      1.778 ms/op
     p(50.0000) =      3.854 ms/op
     p(90.0000) =      4.669 ms/op
     p(95.0000) =      5.161 ms/op
     p(99.0000) =      7.774 ms/op
     p(99.9000) =     26.116 ms/op
     p(99.9900) =     42.674 ms/op
     p(99.9990) =     44.958 ms/op
     p(99.9999) =     45.220 ms/op
    p(100.0000) =     45.220 ms/op


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
# Warmup Iteration   1: 12.772 ±(99.9%) 0.173 ms/op
# Warmup Iteration   2: 4.598 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.119 ±(99.9%) 0.013 ms/op
Iteration   1: 3.905 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.587 ms/op
                 existUser·p0.50:   3.817 ms/op
                 existUser·p0.90:   4.157 ms/op
                 existUser·p0.95:   4.751 ms/op
                 existUser·p0.99:   7.332 ms/op
                 existUser·p0.999:  24.189 ms/op
                 existUser·p0.9999: 26.674 ms/op
                 existUser·p1.00:   27.099 ms/op

Iteration   2: 3.845 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.532 ms/op
                 existUser·p0.50:   3.678 ms/op
                 existUser·p0.90:   4.219 ms/op
                 existUser·p0.95:   4.612 ms/op
                 existUser·p0.99:   7.725 ms/op
                 existUser·p0.999:  17.373 ms/op
                 existUser·p0.9999: 26.804 ms/op
                 existUser·p1.00:   27.197 ms/op

Iteration   3: 3.936 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   1.300 ms/op
                 existUser·p0.50:   3.781 ms/op
                 existUser·p0.90:   4.448 ms/op
                 existUser·p0.95:   4.981 ms/op
                 existUser·p0.99:   7.894 ms/op
                 existUser·p0.999:  26.935 ms/op
                 existUser·p0.9999: 29.942 ms/op
                 existUser·p1.00:   31.949 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 246337
  mean =      3.895 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 313 
    [ 2.500,  5.000) = 235718 
    [ 5.000,  7.500) = 7769 
    [ 7.500, 10.000) = 1488 
    [10.000, 12.500) = 580 
    [12.500, 15.000) = 113 
    [15.000, 17.500) = 74 
    [17.500, 20.000) = 23 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 37 
    [25.000, 27.500) = 151 
    [27.500, 30.000) = 62 
    [30.000, 32.500) = 6 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.300 ms/op
     p(50.0000) =      3.764 ms/op
     p(90.0000) =      4.284 ms/op
     p(95.0000) =      4.817 ms/op
     p(99.0000) =      7.619 ms/op
     p(99.9000) =     24.041 ms/op
     p(99.9900) =     29.089 ms/op
     p(99.9990) =     31.444 ms/op
     p(99.9999) =     31.949 ms/op
    p(100.0000) =     31.949 ms/op


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
# Warmup Iteration   1: 12.348 ±(99.9%) 0.200 ms/op
# Warmup Iteration   2: 4.695 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 4.145 ±(99.9%) 0.015 ms/op
Iteration   1: 4.180 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.409 ms/op
                 getUser·p0.50:   3.912 ms/op
                 getUser·p0.90:   4.989 ms/op
                 getUser·p0.95:   5.571 ms/op
                 getUser·p0.99:   7.855 ms/op
                 getUser·p0.999:  24.281 ms/op
                 getUser·p0.9999: 26.739 ms/op
                 getUser·p1.00:   29.295 ms/op

Iteration   2: 4.006 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.475 ms/op
                 getUser·p0.50:   3.789 ms/op
                 getUser·p0.90:   4.407 ms/op
                 getUser·p0.95:   5.530 ms/op
                 getUser·p0.99:   8.028 ms/op
                 getUser·p0.999:  25.775 ms/op
                 getUser·p0.9999: 29.133 ms/op
                 getUser·p1.00:   29.557 ms/op

Iteration   3: 4.174 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   0.829 ms/op
                 getUser·p0.50:   3.916 ms/op
                 getUser·p0.90:   4.882 ms/op
                 getUser·p0.95:   6.103 ms/op
                 getUser·p0.99:   8.830 ms/op
                 getUser·p0.999:  16.630 ms/op
                 getUser·p0.9999: 37.421 ms/op
                 getUser·p1.00:   37.552 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 233266
  mean =      4.119 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 94 
    [ 2.500,  5.000) = 213936 
    [ 5.000,  7.500) = 15639 
    [ 7.500, 10.000) = 2595 
    [10.000, 12.500) = 549 
    [12.500, 15.000) = 156 
    [15.000, 17.500) = 24 
    [17.500, 20.000) = 17 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 41 
    [25.000, 27.500) = 133 
    [27.500, 30.000) = 49 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 11 
    [35.000, 37.500) = 19 

  Percentiles, ms/op:
      p(0.0000) =      0.829 ms/op
     p(50.0000) =      3.875 ms/op
     p(90.0000) =      4.858 ms/op
     p(95.0000) =      5.702 ms/op
     p(99.0000) =      8.217 ms/op
     p(99.9000) =     24.338 ms/op
     p(99.9900) =     34.909 ms/op
     p(99.9990) =     37.530 ms/op
     p(99.9999) =     37.552 ms/op
    p(100.0000) =     37.552 ms/op


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
# Warmup Iteration   1: 14.611 ±(99.9%) 0.245 ms/op
# Warmup Iteration   2: 5.986 ±(99.9%) 0.036 ms/op
# Warmup Iteration   3: 4.868 ±(99.9%) 0.018 ms/op
Iteration   1: 4.810 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   2.167 ms/op
                 listUser·p0.50:   4.571 ms/op
                 listUser·p0.90:   5.202 ms/op
                 listUser·p0.95:   6.111 ms/op
                 listUser·p0.99:   9.601 ms/op
                 listUser·p0.999:  26.544 ms/op
                 listUser·p0.9999: 29.917 ms/op
                 listUser·p1.00:   30.376 ms/op

Iteration   2: 4.692 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   0.713 ms/op
                 listUser·p0.50:   4.489 ms/op
                 listUser·p0.90:   5.120 ms/op
                 listUser·p0.95:   5.767 ms/op
                 listUser·p0.99:   9.892 ms/op
                 listUser·p0.999:  17.662 ms/op
                 listUser·p0.9999: 25.295 ms/op
                 listUser·p1.00:   25.952 ms/op

Iteration   3: 4.703 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   2.277 ms/op
                 listUser·p0.50:   4.473 ms/op
                 listUser·p0.90:   5.177 ms/op
                 listUser·p0.95:   6.308 ms/op
                 listUser·p0.99:   9.454 ms/op
                 listUser·p0.999:  16.908 ms/op
                 listUser·p0.9999: 19.988 ms/op
                 listUser·p1.00:   20.578 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 202689
  mean =      4.735 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22 
    [ 2.500,  5.000) = 174624 
    [ 5.000,  7.500) = 21717 
    [ 7.500, 10.000) = 4516 
    [10.000, 12.500) = 1058 
    [12.500, 15.000) = 280 
    [15.000, 17.500) = 151 
    [17.500, 20.000) = 96 
    [20.000, 22.500) = 45 
    [22.500, 25.000) = 79 
    [25.000, 27.500) = 41 
    [27.500, 30.000) = 57 
    [30.000, 32.500) = 3 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.713 ms/op
     p(50.0000) =      4.506 ms/op
     p(90.0000) =      5.169 ms/op
     p(95.0000) =      6.021 ms/op
     p(99.0000) =      9.585 ms/op
     p(99.9000) =     21.352 ms/op
     p(99.9900) =     29.342 ms/op
     p(99.9990) =     30.240 ms/op
     p(99.9999) =     30.376 ms/op
    p(100.0000) =     30.376 ms/op


# Run complete. Total time: 00:13:17

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.636 ± 7.434  ops/ms
ClientPb.existUser                       thrpt       3   8.191 ± 2.631  ops/ms
ClientPb.getUser                         thrpt       3   8.043 ± 1.409  ops/ms
ClientPb.listUser                        thrpt       3   6.744 ± 3.004  ops/ms
ClientPb.createUser                       avgt       3   4.021 ± 0.354   ms/op
ClientPb.existUser                        avgt       3   4.139 ± 0.554   ms/op
ClientPb.getUser                          avgt       3   4.197 ± 1.914   ms/op
ClientPb.listUser                         avgt       3   4.838 ± 2.304   ms/op
ClientPb.createUser                     sample  238455   4.028 ± 0.008   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.778           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.854           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.669           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.161           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.774           ms/op
ClientPb.createUser:createUser·p0.999   sample          26.116           ms/op
ClientPb.createUser:createUser·p0.9999  sample          42.674           ms/op
ClientPb.createUser:createUser·p1.00    sample          45.220           ms/op
ClientPb.existUser                      sample  246337   3.895 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.300           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.764           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.284           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.817           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.619           ms/op
ClientPb.existUser:existUser·p0.999     sample          24.041           ms/op
ClientPb.existUser:existUser·p0.9999    sample          29.089           ms/op
ClientPb.existUser:existUser·p1.00      sample          31.949           ms/op
ClientPb.getUser                        sample  233266   4.119 ± 0.008   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.829           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.875           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.858           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.702           ms/op
ClientPb.getUser:getUser·p0.99          sample           8.217           ms/op
ClientPb.getUser:getUser·p0.999         sample          24.338           ms/op
ClientPb.getUser:getUser·p0.9999        sample          34.909           ms/op
ClientPb.getUser:getUser·p1.00          sample          37.552           ms/op
ClientPb.listUser                       sample  202689   4.735 ± 0.009   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.713           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.506           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.169           ms/op
ClientPb.listUser:listUser·p0.95        sample           6.021           ms/op
ClientPb.listUser:listUser·p0.99        sample           9.585           ms/op
ClientPb.listUser:listUser·p0.999       sample          21.352           ms/op
ClientPb.listUser:listUser·p0.9999      sample          29.342           ms/op
ClientPb.listUser:listUser·p1.00        sample          30.376           ms/op
