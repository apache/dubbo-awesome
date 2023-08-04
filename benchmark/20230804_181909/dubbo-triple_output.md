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
# Warmup Iteration   1: 1.507 ops/ms
# Warmup Iteration   2: 3.578 ops/ms
# Warmup Iteration   3: 6.818 ops/ms
Iteration   1: 7.460 ops/ms
Iteration   2: 7.827 ops/ms
Iteration   3: 7.716 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.668 ±(99.9%) 3.430 ops/ms [Average]
  (min, avg, max) = (7.460, 7.668, 7.827), stdev = 0.188
  CI (99.9%): [4.238, 11.097] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:13
# Fork: 1 of 1
# Warmup Iteration   1: 2.141 ops/ms
# Warmup Iteration   2: 6.646 ops/ms
# Warmup Iteration   3: 8.023 ops/ms
Iteration   1: 8.015 ops/ms
Iteration   2: 7.992 ops/ms
Iteration   3: 7.898 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  7.968 ±(99.9%) 1.127 ops/ms [Average]
  (min, avg, max) = (7.898, 7.968, 8.015), stdev = 0.062
  CI (99.9%): [6.841, 9.095] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:02
# Fork: 1 of 1
# Warmup Iteration   1: 2.165 ops/ms
# Warmup Iteration   2: 6.676 ops/ms
# Warmup Iteration   3: 7.878 ops/ms
Iteration   1: 7.957 ops/ms
Iteration   2: 7.852 ops/ms
Iteration   3: 8.093 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.967 ±(99.9%) 2.207 ops/ms [Average]
  (min, avg, max) = (7.852, 7.967, 8.093), stdev = 0.121
  CI (99.9%): [5.761, 10.174] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:57
# Fork: 1 of 1
# Warmup Iteration   1: 1.922 ops/ms
# Warmup Iteration   2: 5.619 ops/ms
# Warmup Iteration   3: 6.327 ops/ms
Iteration   1: 6.646 ops/ms
Iteration   2: 6.813 ops/ms
Iteration   3: 6.799 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.753 ±(99.9%) 1.695 ops/ms [Average]
  (min, avg, max) = (6.646, 6.753, 6.813), stdev = 0.093
  CI (99.9%): [5.058, 8.447] (assumes normal distribution)


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
# Warmup Iteration   1: 13.403 ±(99.9%) 0.082 ms/op
# Warmup Iteration   2: 4.533 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.203 ±(99.9%) 0.005 ms/op
Iteration   1: 4.023 ±(99.9%) 0.006 ms/op
Iteration   2: 4.093 ±(99.9%) 0.010 ms/op
Iteration   3: 3.987 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.035 ±(99.9%) 0.980 ms/op [Average]
  (min, avg, max) = (3.987, 4.035, 4.093), stdev = 0.054
  CI (99.9%): [3.055, 5.015] (assumes normal distribution)


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
# Warmup Iteration   1: 11.780 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 4.794 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.009 ±(99.9%) 0.005 ms/op
Iteration   1: 3.809 ±(99.9%) 0.007 ms/op
Iteration   2: 3.928 ±(99.9%) 0.003 ms/op
Iteration   3: 3.895 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.877 ±(99.9%) 1.125 ms/op [Average]
  (min, avg, max) = (3.809, 3.877, 3.928), stdev = 0.062
  CI (99.9%): [2.752, 5.002] (assumes normal distribution)


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
# Warmup Iteration   1: 11.186 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 4.739 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.279 ±(99.9%) 0.007 ms/op
Iteration   1: 3.997 ±(99.9%) 0.009 ms/op
Iteration   2: 3.897 ±(99.9%) 0.008 ms/op
Iteration   3: 3.923 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.939 ±(99.9%) 0.949 ms/op [Average]
  (min, avg, max) = (3.897, 3.939, 3.997), stdev = 0.052
  CI (99.9%): [2.990, 4.889] (assumes normal distribution)


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
# Warmup Iteration   1: 13.892 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 5.581 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.746 ±(99.9%) 0.006 ms/op
Iteration   1: 4.781 ±(99.9%) 0.006 ms/op
Iteration   2: 4.546 ±(99.9%) 0.009 ms/op
Iteration   3: 4.590 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.639 ±(99.9%) 2.284 ms/op [Average]
  (min, avg, max) = (4.546, 4.639, 4.781), stdev = 0.125
  CI (99.9%): [2.355, 6.923] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 14.050 ±(99.9%) 0.236 ms/op
# Warmup Iteration   2: 5.358 ±(99.9%) 0.032 ms/op
# Warmup Iteration   3: 4.544 ±(99.9%) 0.019 ms/op
Iteration   1: 4.029 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.964 ms/op
                 createUser·p0.50:   3.789 ms/op
                 createUser·p0.90:   4.637 ms/op
                 createUser·p0.95:   5.431 ms/op
                 createUser·p0.99:   8.523 ms/op
                 createUser·p0.999:  14.173 ms/op
                 createUser·p0.9999: 25.790 ms/op
                 createUser·p1.00:   26.542 ms/op

Iteration   2: 4.113 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.968 ms/op
                 createUser·p0.50:   3.920 ms/op
                 createUser·p0.90:   4.833 ms/op
                 createUser·p0.95:   5.439 ms/op
                 createUser·p0.99:   7.684 ms/op
                 createUser·p0.999:  25.829 ms/op
                 createUser·p0.9999: 27.991 ms/op
                 createUser·p1.00:   28.508 ms/op

Iteration   3: 4.169 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   2.054 ms/op
                 createUser·p0.50:   3.957 ms/op
                 createUser·p0.90:   4.882 ms/op
                 createUser·p0.95:   5.480 ms/op
                 createUser·p0.99:   8.151 ms/op
                 createUser·p0.999:  30.024 ms/op
                 createUser·p0.9999: 41.743 ms/op
                 createUser·p1.00:   42.533 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 233979
  mean =      4.103 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 216060 
    [ 5.000, 10.000) = 16660 
    [10.000, 15.000) = 990 
    [15.000, 20.000) = 13 
    [20.000, 25.000) = 51 
    [25.000, 30.000) = 127 
    [30.000, 35.000) = 16 
    [35.000, 40.000) = 34 
    [40.000, 45.000) = 28 

  Percentiles, ms/op:
      p(0.0000) =      1.964 ms/op
     p(50.0000) =      3.908 ms/op
     p(90.0000) =      4.809 ms/op
     p(95.0000) =      5.456 ms/op
     p(99.0000) =      8.045 ms/op
     p(99.9000) =     23.954 ms/op
     p(99.9900) =     40.698 ms/op
     p(99.9990) =     42.511 ms/op
     p(99.9999) =     42.533 ms/op
    p(100.0000) =     42.533 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 12.979 ±(99.9%) 0.211 ms/op
# Warmup Iteration   2: 4.402 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.857 ±(99.9%) 0.013 ms/op
Iteration   1: 3.985 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.657 ms/op
                 existUser·p0.50:   3.789 ms/op
                 existUser·p0.90:   4.612 ms/op
                 existUser·p0.95:   5.358 ms/op
                 existUser·p0.99:   7.504 ms/op
                 existUser·p0.999:  12.337 ms/op
                 existUser·p0.9999: 26.017 ms/op
                 existUser·p1.00:   26.444 ms/op

Iteration   2: 3.898 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.272 ms/op
                 existUser·p0.50:   3.711 ms/op
                 existUser·p0.90:   4.424 ms/op
                 existUser·p0.95:   4.973 ms/op
                 existUser·p0.99:   7.307 ms/op
                 existUser·p0.999:  12.239 ms/op
                 existUser·p0.9999: 27.399 ms/op
                 existUser·p1.00:   28.377 ms/op

Iteration   3: 3.912 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   1.413 ms/op
                 existUser·p0.50:   3.768 ms/op
                 existUser·p0.90:   4.284 ms/op
                 existUser·p0.95:   5.235 ms/op
                 existUser·p0.99:   8.046 ms/op
                 existUser·p0.999:  26.280 ms/op
                 existUser·p0.9999: 30.278 ms/op
                 existUser·p1.00:   32.735 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 243997
  mean =      3.931 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 322 
    [ 2.500,  5.000) = 229655 
    [ 5.000,  7.500) = 11471 
    [ 7.500, 10.000) = 1760 
    [10.000, 12.500) = 442 
    [12.500, 15.000) = 121 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 42 
    [25.000, 27.500) = 112 
    [27.500, 30.000) = 52 
    [30.000, 32.500) = 10 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.272 ms/op
     p(50.0000) =      3.756 ms/op
     p(90.0000) =      4.456 ms/op
     p(95.0000) =      5.186 ms/op
     p(99.0000) =      7.545 ms/op
     p(99.9000) =     13.664 ms/op
     p(99.9900) =     29.327 ms/op
     p(99.9990) =     31.058 ms/op
     p(99.9999) =     32.735 ms/op
    p(100.0000) =     32.735 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:13
# Fork: 1 of 1
# Warmup Iteration   1: 13.516 ±(99.9%) 0.208 ms/op
# Warmup Iteration   2: 4.756 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 4.563 ±(99.9%) 0.018 ms/op
Iteration   1: 4.054 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.649 ms/op
                 getUser·p0.50:   3.912 ms/op
                 getUser·p0.90:   4.383 ms/op
                 getUser·p0.95:   4.637 ms/op
                 getUser·p0.99:   8.117 ms/op
                 getUser·p0.999:  25.264 ms/op
                 getUser·p0.9999: 31.598 ms/op
                 getUser·p1.00:   32.080 ms/op

Iteration   2: 4.019 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.352 ms/op
                 getUser·p0.50:   3.863 ms/op
                 getUser·p0.90:   4.366 ms/op
                 getUser·p0.95:   4.678 ms/op
                 getUser·p0.99:   7.548 ms/op
                 getUser·p0.999:  26.651 ms/op
                 getUser·p0.9999: 40.763 ms/op
                 getUser·p1.00:   41.550 ms/op

Iteration   3: 4.089 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   2.009 ms/op
                 getUser·p0.50:   3.850 ms/op
                 getUser·p0.90:   4.702 ms/op
                 getUser·p0.95:   5.472 ms/op
                 getUser·p0.99:   7.963 ms/op
                 getUser·p0.999:  13.792 ms/op
                 getUser·p0.9999: 29.301 ms/op
                 getUser·p1.00:   30.015 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 236913
  mean =      4.054 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 225210 
    [ 5.000, 10.000) = 10779 
    [10.000, 15.000) = 657 
    [15.000, 20.000) = 21 
    [20.000, 25.000) = 11 
    [25.000, 30.000) = 151 
    [30.000, 35.000) = 52 
    [35.000, 40.000) = 17 
    [40.000, 45.000) = 15 

  Percentiles, ms/op:
      p(0.0000) =      1.352 ms/op
     p(50.0000) =      3.875 ms/op
     p(90.0000) =      4.456 ms/op
     p(95.0000) =      4.981 ms/op
     p(99.0000) =      7.864 ms/op
     p(99.9000) =     24.517 ms/op
     p(99.9900) =     38.928 ms/op
     p(99.9990) =     41.001 ms/op
     p(99.9999) =     41.550 ms/op
    p(100.0000) =     41.550 ms/op


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
# Warmup Iteration   1: 14.916 ±(99.9%) 0.229 ms/op
# Warmup Iteration   2: 5.506 ±(99.9%) 0.031 ms/op
# Warmup Iteration   3: 4.961 ±(99.9%) 0.019 ms/op
Iteration   1: 4.905 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   2.384 ms/op
                 listUser·p0.50:   4.497 ms/op
                 listUser·p0.90:   5.874 ms/op
                 listUser·p0.95:   7.602 ms/op
                 listUser·p0.99:   10.383 ms/op
                 listUser·p0.999:  26.109 ms/op
                 listUser·p0.9999: 27.836 ms/op
                 listUser·p1.00:   32.211 ms/op

Iteration   2: 4.883 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   2.396 ms/op
                 listUser·p0.50:   4.612 ms/op
                 listUser·p0.90:   5.513 ms/op
                 listUser·p0.95:   6.499 ms/op
                 listUser·p0.99:   9.699 ms/op
                 listUser·p0.999:  22.661 ms/op
                 listUser·p0.9999: 28.809 ms/op
                 listUser·p1.00:   29.884 ms/op

Iteration   3: 4.884 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.997 ms/op
                 listUser·p0.50:   4.555 ms/op
                 listUser·p0.90:   5.538 ms/op
                 listUser·p0.95:   7.495 ms/op
                 listUser·p0.99:   10.082 ms/op
                 listUser·p0.999:  17.450 ms/op
                 listUser·p0.9999: 25.559 ms/op
                 listUser·p1.00:   25.690 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 196137
  mean =      4.891 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10 
    [ 2.500,  5.000) = 153381 
    [ 5.000,  7.500) = 34053 
    [ 7.500, 10.000) = 6692 
    [10.000, 12.500) = 1127 
    [12.500, 15.000) = 437 
    [15.000, 17.500) = 132 
    [17.500, 20.000) = 55 
    [20.000, 22.500) = 39 
    [22.500, 25.000) = 59 
    [25.000, 27.500) = 133 
    [27.500, 30.000) = 18 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.997 ms/op
     p(50.0000) =      4.563 ms/op
     p(90.0000) =      5.628 ms/op
     p(95.0000) =      7.217 ms/op
     p(99.0000) =     10.060 ms/op
     p(99.9000) =     23.069 ms/op
     p(99.9900) =     27.528 ms/op
     p(99.9990) =     29.974 ms/op
     p(99.9999) =     32.211 ms/op
    p(100.0000) =     32.211 ms/op


# Run complete. Total time: 00:13:19

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.668 ± 3.430  ops/ms
ClientPb.existUser                       thrpt       3   7.968 ± 1.127  ops/ms
ClientPb.getUser                         thrpt       3   7.967 ± 2.207  ops/ms
ClientPb.listUser                        thrpt       3   6.753 ± 1.695  ops/ms
ClientPb.createUser                       avgt       3   4.035 ± 0.980   ms/op
ClientPb.existUser                        avgt       3   3.877 ± 1.125   ms/op
ClientPb.getUser                          avgt       3   3.939 ± 0.949   ms/op
ClientPb.listUser                         avgt       3   4.639 ± 2.284   ms/op
ClientPb.createUser                     sample  233979   4.103 ± 0.008   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.964           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.908           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.809           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.456           ms/op
ClientPb.createUser:createUser·p0.99    sample           8.045           ms/op
ClientPb.createUser:createUser·p0.999   sample          23.954           ms/op
ClientPb.createUser:createUser·p0.9999  sample          40.698           ms/op
ClientPb.createUser:createUser·p1.00    sample          42.533           ms/op
ClientPb.existUser                      sample  243997   3.931 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.272           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.756           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.456           ms/op
ClientPb.existUser:existUser·p0.95      sample           5.186           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.545           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.664           ms/op
ClientPb.existUser:existUser·p0.9999    sample          29.327           ms/op
ClientPb.existUser:existUser·p1.00      sample          32.735           ms/op
ClientPb.getUser                        sample  236913   4.054 ± 0.008   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.352           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.875           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.456           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.981           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.864           ms/op
ClientPb.getUser:getUser·p0.999         sample          24.517           ms/op
ClientPb.getUser:getUser·p0.9999        sample          38.928           ms/op
ClientPb.getUser:getUser·p1.00          sample          41.550           ms/op
ClientPb.listUser                       sample  196137   4.891 ± 0.010   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.997           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.563           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.628           ms/op
ClientPb.listUser:listUser·p0.95        sample           7.217           ms/op
ClientPb.listUser:listUser·p0.99        sample          10.060           ms/op
ClientPb.listUser:listUser·p0.999       sample          23.069           ms/op
ClientPb.listUser:listUser·p0.9999      sample          27.528           ms/op
ClientPb.listUser:listUser·p1.00        sample          32.211           ms/op
