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
# Warmup Iteration   1: 2.558 ops/ms
# Warmup Iteration   2: 6.123 ops/ms
# Warmup Iteration   3: 8.820 ops/ms
Iteration   1: 9.297 ops/ms
Iteration   2: 9.459 ops/ms
Iteration   3: 9.899 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.552 ±(99.9%) 5.681 ops/ms [Average]
  (min, avg, max) = (9.297, 9.552, 9.899), stdev = 0.311
  CI (99.9%): [3.871, 15.232] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 3.456 ops/ms
# Warmup Iteration   2: 9.273 ops/ms
# Warmup Iteration   3: 9.897 ops/ms
Iteration   1: 10.152 ops/ms
Iteration   2: 9.940 ops/ms
Iteration   3: 10.406 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.166 ±(99.9%) 4.257 ops/ms [Average]
  (min, avg, max) = (9.940, 10.166, 10.406), stdev = 0.233
  CI (99.9%): [5.909, 14.423] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 3.615 ops/ms
# Warmup Iteration   2: 8.926 ops/ms
# Warmup Iteration   3: 9.931 ops/ms
Iteration   1: 9.657 ops/ms
Iteration   2: 9.923 ops/ms
Iteration   3: 10.058 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.879 ±(99.9%) 3.723 ops/ms [Average]
  (min, avg, max) = (9.657, 9.879, 10.058), stdev = 0.204
  CI (99.9%): [6.156, 13.603] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 3.644 ops/ms
# Warmup Iteration   2: 7.646 ops/ms
# Warmup Iteration   3: 8.222 ops/ms
Iteration   1: 8.328 ops/ms
Iteration   2: 8.180 ops/ms
Iteration   3: 8.330 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.280 ±(99.9%) 1.566 ops/ms [Average]
  (min, avg, max) = (8.180, 8.280, 8.330), stdev = 0.086
  CI (99.9%): [6.714, 9.845] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 8.551 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.515 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.625 ±(99.9%) 0.004 ms/op
Iteration   1: 3.239 ±(99.9%) 0.008 ms/op
Iteration   2: 3.352 ±(99.9%) 0.009 ms/op
Iteration   3: 3.378 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.323 ±(99.9%) 1.344 ms/op [Average]
  (min, avg, max) = (3.239, 3.323, 3.378), stdev = 0.074
  CI (99.9%): [1.979, 4.667] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 7.311 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.362 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.196 ±(99.9%) 0.004 ms/op
Iteration   1: 3.080 ±(99.9%) 0.004 ms/op
Iteration   2: 3.131 ±(99.9%) 0.007 ms/op
Iteration   3: 3.119 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.110 ±(99.9%) 0.489 ms/op [Average]
  (min, avg, max) = (3.080, 3.110, 3.131), stdev = 0.027
  CI (99.9%): [2.621, 3.599] (assumes normal distribution)


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
# Warmup Iteration   1: 8.128 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.419 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.400 ±(99.9%) 0.008 ms/op
Iteration   1: 3.214 ±(99.9%) 0.004 ms/op
Iteration   2: 3.224 ±(99.9%) 0.004 ms/op
Iteration   3: 3.245 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.227 ±(99.9%) 0.287 ms/op [Average]
  (min, avg, max) = (3.214, 3.227, 3.245), stdev = 0.016
  CI (99.9%): [2.940, 3.514] (assumes normal distribution)


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
# Warmup Iteration   1: 9.045 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 4.067 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.853 ±(99.9%) 0.004 ms/op
Iteration   1: 3.800 ±(99.9%) 0.010 ms/op
Iteration   2: 3.817 ±(99.9%) 0.005 ms/op
Iteration   3: 3.714 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.777 ±(99.9%) 1.009 ms/op [Average]
  (min, avg, max) = (3.714, 3.777, 3.817), stdev = 0.055
  CI (99.9%): [2.768, 4.786] (assumes normal distribution)


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
# Warmup Iteration   1: 8.634 ±(99.9%) 0.096 ms/op
# Warmup Iteration   2: 3.784 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.274 ±(99.9%) 0.010 ms/op
Iteration   1: 3.289 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.442 ms/op
                 createUser·p0.50:   3.248 ms/op
                 createUser·p0.90:   3.674 ms/op
                 createUser·p0.95:   4.088 ms/op
                 createUser·p0.99:   5.636 ms/op
                 createUser·p0.999:  14.296 ms/op
                 createUser·p0.9999: 20.063 ms/op
                 createUser·p1.00:   20.906 ms/op

Iteration   2: 3.317 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.227 ms/op
                 createUser·p0.50:   3.170 ms/op
                 createUser·p0.90:   3.760 ms/op
                 createUser·p0.95:   4.465 ms/op
                 createUser·p0.99:   6.472 ms/op
                 createUser·p0.999:  20.793 ms/op
                 createUser·p0.9999: 34.041 ms/op
                 createUser·p1.00:   35.389 ms/op

Iteration   3: 3.278 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.522 ms/op
                 createUser·p0.50:   3.240 ms/op
                 createUser·p0.90:   3.588 ms/op
                 createUser·p0.95:   3.990 ms/op
                 createUser·p0.99:   6.119 ms/op
                 createUser·p0.999:  16.847 ms/op
                 createUser·p0.9999: 23.937 ms/op
                 createUser·p1.00:   24.543 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 291131
  mean =      3.295 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22824 
    [ 2.500,  5.000) = 260167 
    [ 5.000,  7.500) = 6711 
    [ 7.500, 10.000) = 883 
    [10.000, 12.500) = 184 
    [12.500, 15.000) = 11 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 129 
    [20.000, 22.500) = 124 
    [22.500, 25.000) = 35 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 6 
    [32.500, 35.000) = 21 
    [35.000, 37.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      1.227 ms/op
     p(50.0000) =      3.232 ms/op
     p(90.0000) =      3.678 ms/op
     p(95.0000) =      4.157 ms/op
     p(99.0000) =      6.169 ms/op
     p(99.9000) =     18.514 ms/op
     p(99.9900) =     32.367 ms/op
     p(99.9990) =     35.204 ms/op
     p(99.9999) =     35.389 ms/op
    p(100.0000) =     35.389 ms/op


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
# Warmup Iteration   1: 7.147 ±(99.9%) 0.086 ms/op
# Warmup Iteration   2: 3.354 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.135 ±(99.9%) 0.008 ms/op
Iteration   1: 3.087 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.147 ms/op
                 existUser·p0.50:   3.064 ms/op
                 existUser·p0.90:   3.248 ms/op
                 existUser·p0.95:   3.457 ms/op
                 existUser·p0.99:   5.505 ms/op
                 existUser·p0.999:  12.059 ms/op
                 existUser·p0.9999: 22.184 ms/op
                 existUser·p1.00:   22.577 ms/op

Iteration   2: 3.229 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.389 ms/op
                 existUser·p0.50:   3.142 ms/op
                 existUser·p0.90:   3.559 ms/op
                 existUser·p0.95:   4.076 ms/op
                 existUser·p0.99:   6.496 ms/op
                 existUser·p0.999:  13.927 ms/op
                 existUser·p0.9999: 22.970 ms/op
                 existUser·p1.00:   24.379 ms/op

Iteration   3: 3.095 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.255 ms/op
                 existUser·p0.50:   3.060 ms/op
                 existUser·p0.90:   3.260 ms/op
                 existUser·p0.95:   3.441 ms/op
                 existUser·p0.99:   5.997 ms/op
                 existUser·p0.999:  10.074 ms/op
                 existUser·p0.9999: 24.237 ms/op
                 existUser·p1.00:   25.002 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 305983
  mean =      3.136 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18659 
    [ 2.500,  5.000) = 281188 
    [ 5.000,  7.500) = 4846 
    [ 7.500, 10.000) = 936 
    [10.000, 12.500) = 63 
    [12.500, 15.000) = 14 
    [15.000, 17.500) = 21 
    [17.500, 20.000) = 37 
    [20.000, 22.500) = 170 
    [22.500, 25.000) = 48 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.147 ms/op
     p(50.0000) =      3.084 ms/op
     p(90.0000) =      3.359 ms/op
     p(95.0000) =      3.641 ms/op
     p(99.0000) =      6.038 ms/op
     p(99.9000) =     11.715 ms/op
     p(99.9900) =     23.311 ms/op
     p(99.9990) =     24.701 ms/op
     p(99.9999) =     25.002 ms/op
    p(100.0000) =     25.002 ms/op


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
# Warmup Iteration   1: 7.738 ±(99.9%) 0.094 ms/op
# Warmup Iteration   2: 3.553 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.344 ±(99.9%) 0.011 ms/op
Iteration   1: 3.420 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.031 ms/op
                 getUser·p0.50:   3.174 ms/op
                 getUser·p0.90:   3.920 ms/op
                 getUser·p0.95:   5.792 ms/op
                 getUser·p0.99:   7.225 ms/op
                 getUser·p0.999:  17.695 ms/op
                 getUser·p0.9999: 23.385 ms/op
                 getUser·p1.00:   23.822 ms/op

Iteration   2: 3.295 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.011 ms/op
                 getUser·p0.50:   3.170 ms/op
                 getUser·p0.90:   3.805 ms/op
                 getUser·p0.95:   4.235 ms/op
                 getUser·p0.99:   5.962 ms/op
                 getUser·p0.999:  12.508 ms/op
                 getUser·p0.9999: 22.498 ms/op
                 getUser·p1.00:   23.069 ms/op

Iteration   3: 3.215 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.264 ms/op
                 getUser·p0.50:   3.092 ms/op
                 getUser·p0.90:   3.486 ms/op
                 getUser·p0.95:   3.891 ms/op
                 getUser·p0.99:   5.816 ms/op
                 getUser·p0.999:  11.370 ms/op
                 getUser·p0.9999: 22.165 ms/op
                 getUser·p1.00:   23.167 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 289882
  mean =      3.308 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10949 
    [ 2.500,  5.000) = 266778 
    [ 5.000,  7.500) = 10590 
    [ 7.500, 10.000) = 1082 
    [10.000, 12.500) = 193 
    [12.500, 15.000) = 28 
    [15.000, 17.500) = 24 
    [17.500, 20.000) = 104 
    [20.000, 22.500) = 102 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.011 ms/op
     p(50.0000) =      3.142 ms/op
     p(90.0000) =      3.723 ms/op
     p(95.0000) =      4.530 ms/op
     p(99.0000) =      6.799 ms/op
     p(99.9000) =     12.652 ms/op
     p(99.9900) =     22.578 ms/op
     p(99.9990) =     23.763 ms/op
     p(99.9999) =     23.822 ms/op
    p(100.0000) =     23.822 ms/op


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
# Warmup Iteration   1: 9.142 ±(99.9%) 0.124 ms/op
# Warmup Iteration   2: 4.199 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.973 ±(99.9%) 0.013 ms/op
Iteration   1: 3.825 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.380 ms/op
                 listUser·p0.50:   3.699 ms/op
                 listUser·p0.90:   4.104 ms/op
                 listUser·p0.95:   4.424 ms/op
                 listUser·p0.99:   7.700 ms/op
                 listUser·p0.999:  15.921 ms/op
                 listUser·p0.9999: 37.791 ms/op
                 listUser·p1.00:   38.994 ms/op

Iteration   2: 3.740 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.982 ms/op
                 listUser·p0.50:   3.621 ms/op
                 listUser·p0.90:   3.998 ms/op
                 listUser·p0.95:   4.276 ms/op
                 listUser·p0.99:   7.193 ms/op
                 listUser·p0.999:  13.664 ms/op
                 listUser·p0.9999: 20.148 ms/op
                 listUser·p1.00:   20.513 ms/op

Iteration   3: 3.832 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.204 ms/op
                 listUser·p0.50:   3.711 ms/op
                 listUser·p0.90:   4.084 ms/op
                 listUser·p0.95:   4.375 ms/op
                 listUser·p0.99:   7.643 ms/op
                 listUser·p0.999:  15.178 ms/op
                 listUser·p0.9999: 19.005 ms/op
                 listUser·p1.00:   19.923 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 252641
  mean =      3.799 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 57 
    [ 2.500,  5.000) = 243887 
    [ 5.000,  7.500) = 6147 
    [ 7.500, 10.000) = 1810 
    [10.000, 12.500) = 234 
    [12.500, 15.000) = 263 
    [15.000, 17.500) = 110 
    [17.500, 20.000) = 66 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 23 

  Percentiles, ms/op:
      p(0.0000) =      1.380 ms/op
     p(50.0000) =      3.674 ms/op
     p(90.0000) =      4.071 ms/op
     p(95.0000) =      4.350 ms/op
     p(99.0000) =      7.528 ms/op
     p(99.9000) =     14.751 ms/op
     p(99.9900) =     36.307 ms/op
     p(99.9990) =     38.759 ms/op
     p(99.9999) =     38.994 ms/op
    p(100.0000) =     38.994 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.552 ± 5.681  ops/ms
ClientPb.existUser                       thrpt       3  10.166 ± 4.257  ops/ms
ClientPb.getUser                         thrpt       3   9.879 ± 3.723  ops/ms
ClientPb.listUser                        thrpt       3   8.280 ± 1.566  ops/ms
ClientPb.createUser                       avgt       3   3.323 ± 1.344   ms/op
ClientPb.existUser                        avgt       3   3.110 ± 0.489   ms/op
ClientPb.getUser                          avgt       3   3.227 ± 0.287   ms/op
ClientPb.listUser                         avgt       3   3.777 ± 1.009   ms/op
ClientPb.createUser                     sample  291131   3.295 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.227           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.232           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.678           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.157           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.169           ms/op
ClientPb.createUser:createUser·p0.999   sample          18.514           ms/op
ClientPb.createUser:createUser·p0.9999  sample          32.367           ms/op
ClientPb.createUser:createUser·p1.00    sample          35.389           ms/op
ClientPb.existUser                      sample  305983   3.136 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.147           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.084           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.359           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.641           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.038           ms/op
ClientPb.existUser:existUser·p0.999     sample          11.715           ms/op
ClientPb.existUser:existUser·p0.9999    sample          23.311           ms/op
ClientPb.existUser:existUser·p1.00      sample          25.002           ms/op
ClientPb.getUser                        sample  289882   3.308 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.011           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.142           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.723           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.530           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.799           ms/op
ClientPb.getUser:getUser·p0.999         sample          12.652           ms/op
ClientPb.getUser:getUser·p0.9999        sample          22.578           ms/op
ClientPb.getUser:getUser·p1.00          sample          23.822           ms/op
ClientPb.listUser                       sample  252641   3.799 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.380           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.674           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.071           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.350           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.528           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.751           ms/op
ClientPb.listUser:listUser·p0.9999      sample          36.307           ms/op
ClientPb.listUser:listUser·p1.00        sample          38.994           ms/op
