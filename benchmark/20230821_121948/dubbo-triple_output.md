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
# Warmup Iteration   1: 1.504 ops/ms
# Warmup Iteration   2: 4.035 ops/ms
# Warmup Iteration   3: 6.343 ops/ms
Iteration   1: 6.066 ops/ms
Iteration   2: 6.721 ops/ms
Iteration   3: 6.625 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  6.471 ±(99.9%) 6.449 ops/ms [Average]
  (min, avg, max) = (6.066, 6.471, 6.721), stdev = 0.353
  CI (99.9%): [0.022, 12.919] (assumes normal distribution)


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
# Warmup Iteration   1: 2.128 ops/ms
# Warmup Iteration   2: 6.245 ops/ms
# Warmup Iteration   3: 7.087 ops/ms
Iteration   1: 7.347 ops/ms
Iteration   2: 7.311 ops/ms
Iteration   3: 7.128 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  7.262 ±(99.9%) 2.142 ops/ms [Average]
  (min, avg, max) = (7.128, 7.262, 7.347), stdev = 0.117
  CI (99.9%): [5.120, 9.404] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:59
# Fork: 1 of 1
# Warmup Iteration   1: 2.137 ops/ms
# Warmup Iteration   2: 5.620 ops/ms
# Warmup Iteration   3: 6.784 ops/ms
Iteration   1: 6.702 ops/ms
Iteration   2: 6.795 ops/ms
Iteration   3: 6.652 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  6.716 ±(99.9%) 1.323 ops/ms [Average]
  (min, avg, max) = (6.652, 6.716, 6.795), stdev = 0.073
  CI (99.9%): [5.393, 8.039] (assumes normal distribution)


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
# Warmup Iteration   1: 2.194 ops/ms
# Warmup Iteration   2: 5.193 ops/ms
# Warmup Iteration   3: 5.522 ops/ms
Iteration   1: 5.917 ops/ms
Iteration   2: 6.043 ops/ms
Iteration   3: 5.890 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.950 ±(99.9%) 1.496 ops/ms [Average]
  (min, avg, max) = (5.890, 5.950, 6.043), stdev = 0.082
  CI (99.9%): [4.454, 7.446] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:49
# Fork: 1 of 1
# Warmup Iteration   1: 14.774 ±(99.9%) 0.067 ms/op
# Warmup Iteration   2: 5.522 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 5.179 ±(99.9%) 0.013 ms/op
Iteration   1: 4.926 ±(99.9%) 0.019 ms/op
Iteration   2: 4.855 ±(99.9%) 0.016 ms/op
Iteration   3: 4.822 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.868 ±(99.9%) 0.974 ms/op [Average]
  (min, avg, max) = (4.822, 4.868, 4.926), stdev = 0.053
  CI (99.9%): [3.894, 5.842] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 13.308 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 4.899 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.711 ±(99.9%) 0.010 ms/op
Iteration   1: 4.585 ±(99.9%) 0.009 ms/op
Iteration   2: 4.414 ±(99.9%) 0.015 ms/op
Iteration   3: 4.578 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  4.525 ±(99.9%) 1.762 ms/op [Average]
  (min, avg, max) = (4.414, 4.525, 4.585), stdev = 0.097
  CI (99.9%): [2.763, 6.288] (assumes normal distribution)


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
# Warmup Iteration   1: 16.279 ±(99.9%) 0.062 ms/op
# Warmup Iteration   2: 5.546 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 5.011 ±(99.9%) 0.011 ms/op
Iteration   1: 5.257 ±(99.9%) 0.007 ms/op
Iteration   2: 4.895 ±(99.9%) 0.009 ms/op
Iteration   3: 4.805 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.986 ±(99.9%) 4.360 ms/op [Average]
  (min, avg, max) = (4.805, 4.986, 5.257), stdev = 0.239
  CI (99.9%): [0.626, 9.345] (assumes normal distribution)


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
# Warmup Iteration   1: 15.041 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 6.200 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 5.361 ±(99.9%) 0.010 ms/op
Iteration   1: 5.562 ±(99.9%) 0.017 ms/op
Iteration   2: 5.702 ±(99.9%) 0.011 ms/op
Iteration   3: 5.562 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.609 ±(99.9%) 1.472 ms/op [Average]
  (min, avg, max) = (5.562, 5.609, 5.702), stdev = 0.081
  CI (99.9%): [4.137, 7.081] (assumes normal distribution)


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
# Warmup Iteration   1: 14.341 ±(99.9%) 0.230 ms/op
# Warmup Iteration   2: 6.305 ±(99.9%) 0.038 ms/op
# Warmup Iteration   3: 5.140 ±(99.9%) 0.020 ms/op
Iteration   1: 4.812 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   2.097 ms/op
                 createUser·p0.50:   4.588 ms/op
                 createUser·p0.90:   6.029 ms/op
                 createUser·p0.95:   6.726 ms/op
                 createUser·p0.99:   8.782 ms/op
                 createUser·p0.999:  22.492 ms/op
                 createUser·p0.9999: 28.214 ms/op
                 createUser·p1.00:   29.295 ms/op

Iteration   2: 4.763 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   2.327 ms/op
                 createUser·p0.50:   4.489 ms/op
                 createUser·p0.90:   5.964 ms/op
                 createUser·p0.95:   6.742 ms/op
                 createUser·p0.99:   9.421 ms/op
                 createUser·p0.999:  17.039 ms/op
                 createUser·p0.9999: 28.574 ms/op
                 createUser·p1.00:   29.262 ms/op

Iteration   3: 5.048 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   1.831 ms/op
                 createUser·p0.50:   4.809 ms/op
                 createUser·p0.90:   6.218 ms/op
                 createUser·p0.95:   7.078 ms/op
                 createUser·p0.99:   9.814 ms/op
                 createUser·p0.999:  27.140 ms/op
                 createUser·p0.9999: 33.772 ms/op
                 createUser·p1.00:   35.455 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 197125
  mean =      4.871 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 75 
    [ 2.500,  5.000) = 134242 
    [ 5.000,  7.500) = 57292 
    [ 7.500, 10.000) = 4049 
    [10.000, 12.500) = 927 
    [12.500, 15.000) = 239 
    [15.000, 17.500) = 40 
    [17.500, 20.000) = 4 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 37 
    [25.000, 27.500) = 96 
    [27.500, 30.000) = 58 
    [30.000, 32.500) = 18 
    [32.500, 35.000) = 17 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.831 ms/op
     p(50.0000) =      4.612 ms/op
     p(90.0000) =      6.070 ms/op
     p(95.0000) =      6.824 ms/op
     p(99.0000) =      9.306 ms/op
     p(99.9000) =     24.244 ms/op
     p(99.9900) =     32.440 ms/op
     p(99.9990) =     34.882 ms/op
     p(99.9999) =     35.455 ms/op
    p(100.0000) =     35.455 ms/op


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
# Warmup Iteration   1: 13.018 ±(99.9%) 0.179 ms/op
# Warmup Iteration   2: 5.129 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 4.740 ±(99.9%) 0.015 ms/op
Iteration   1: 4.502 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.720 ms/op
                 existUser·p0.50:   4.301 ms/op
                 existUser·p0.90:   5.366 ms/op
                 existUser·p0.95:   6.005 ms/op
                 existUser·p0.99:   8.531 ms/op
                 existUser·p0.999:  14.057 ms/op
                 existUser·p0.9999: 21.561 ms/op
                 existUser·p1.00:   21.889 ms/op

Iteration   2: 4.619 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   1.892 ms/op
                 existUser·p0.50:   4.415 ms/op
                 existUser·p0.90:   5.579 ms/op
                 existUser·p0.95:   6.193 ms/op
                 existUser·p0.99:   8.913 ms/op
                 existUser·p0.999:  16.277 ms/op
                 existUser·p0.9999: 22.219 ms/op
                 existUser·p1.00:   22.675 ms/op

Iteration   3: 4.683 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   2.046 ms/op
                 existUser·p0.50:   4.399 ms/op
                 existUser·p0.90:   6.111 ms/op
                 existUser·p0.95:   6.726 ms/op
                 existUser·p0.99:   8.438 ms/op
                 existUser·p0.999:  14.922 ms/op
                 existUser·p0.9999: 24.526 ms/op
                 existUser·p1.00:   25.133 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 208438
  mean =      4.600 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 159 
    [ 2.500,  5.000) = 165721 
    [ 5.000,  7.500) = 38123 
    [ 7.500, 10.000) = 3309 
    [10.000, 12.500) = 700 
    [12.500, 15.000) = 209 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 69 
    [20.000, 22.500) = 77 
    [22.500, 25.000) = 36 
    [25.000, 27.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      1.720 ms/op
     p(50.0000) =      4.366 ms/op
     p(90.0000) =      5.636 ms/op
     p(95.0000) =      6.398 ms/op
     p(99.0000) =      8.618 ms/op
     p(99.9000) =     15.459 ms/op
     p(99.9900) =     23.182 ms/op
     p(99.9990) =     25.062 ms/op
     p(99.9999) =     25.133 ms/op
    p(100.0000) =     25.133 ms/op


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
# Warmup Iteration   1: 14.397 ±(99.9%) 0.190 ms/op
# Warmup Iteration   2: 5.207 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 4.905 ±(99.9%) 0.018 ms/op
Iteration   1: 5.105 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   2.290 ms/op
                 getUser·p0.50:   4.768 ms/op
                 getUser·p0.90:   6.357 ms/op
                 getUser·p0.95:   7.348 ms/op
                 getUser·p0.99:   11.190 ms/op
                 getUser·p0.999:  20.808 ms/op
                 getUser·p0.9999: 26.140 ms/op
                 getUser·p1.00:   26.968 ms/op

Iteration   2: 5.252 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   2.736 ms/op
                 getUser·p0.50:   4.866 ms/op
                 getUser·p0.90:   6.775 ms/op
                 getUser·p0.95:   8.102 ms/op
                 getUser·p0.99:   11.076 ms/op
                 getUser·p0.999:  15.288 ms/op
                 getUser·p0.9999: 31.031 ms/op
                 getUser·p1.00:   32.276 ms/op

Iteration   3: 5.258 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   1.958 ms/op
                 getUser·p0.50:   5.014 ms/op
                 getUser·p0.90:   6.431 ms/op
                 getUser·p0.95:   7.447 ms/op
                 getUser·p0.99:   10.060 ms/op
                 getUser·p0.999:  26.495 ms/op
                 getUser·p0.9999: 29.977 ms/op
                 getUser·p1.00:   30.409 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 184343
  mean =      5.204 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19 
    [ 2.500,  5.000) = 103498 
    [ 5.000,  7.500) = 70720 
    [ 7.500, 10.000) = 7317 
    [10.000, 12.500) = 1900 
    [12.500, 15.000) = 488 
    [15.000, 17.500) = 181 
    [17.500, 20.000) = 45 
    [20.000, 22.500) = 36 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 39 
    [27.500, 30.000) = 40 
    [30.000, 32.500) = 32 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.958 ms/op
     p(50.0000) =      4.874 ms/op
     p(90.0000) =      6.480 ms/op
     p(95.0000) =      7.676 ms/op
     p(99.0000) =     10.977 ms/op
     p(99.9000) =     18.874 ms/op
     p(99.9900) =     30.558 ms/op
     p(99.9990) =     31.503 ms/op
     p(99.9999) =     32.276 ms/op
    p(100.0000) =     32.276 ms/op


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
# Warmup Iteration   1: 17.338 ±(99.9%) 0.286 ms/op
# Warmup Iteration   2: 6.569 ±(99.9%) 0.039 ms/op
# Warmup Iteration   3: 5.504 ±(99.9%) 0.024 ms/op
Iteration   1: 5.421 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   1.950 ms/op
                 listUser·p0.50:   5.120 ms/op
                 listUser·p0.90:   6.480 ms/op
                 listUser·p0.95:   7.397 ms/op
                 listUser·p0.99:   10.535 ms/op
                 listUser·p0.999:  24.052 ms/op
                 listUser·p0.9999: 26.229 ms/op
                 listUser·p1.00:   27.492 ms/op

Iteration   2: 5.656 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   1.597 ms/op
                 listUser·p0.50:   5.407 ms/op
                 listUser·p0.90:   6.595 ms/op
                 listUser·p0.95:   7.397 ms/op
                 listUser·p0.99:   11.420 ms/op
                 listUser·p0.999:  22.316 ms/op
                 listUser·p0.9999: 25.166 ms/op
                 listUser·p1.00:   26.345 ms/op

Iteration   3: 5.466 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   2.945 ms/op
                 listUser·p0.50:   5.267 ms/op
                 listUser·p0.90:   6.242 ms/op
                 listUser·p0.95:   6.963 ms/op
                 listUser·p0.99:   10.322 ms/op
                 listUser·p0.999:  17.513 ms/op
                 listUser·p0.9999: 23.069 ms/op
                 listUser·p1.00:   23.167 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 173988
  mean =      5.512 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9 
    [ 2.500,  5.000) = 56348 
    [ 5.000,  7.500) = 110004 
    [ 7.500, 10.000) = 5168 
    [10.000, 12.500) = 1574 
    [12.500, 15.000) = 443 
    [15.000, 17.500) = 145 
    [17.500, 20.000) = 65 
    [20.000, 22.500) = 78 
    [22.500, 25.000) = 120 
    [25.000, 27.500) = 34 

  Percentiles, ms/op:
      p(0.0000) =      1.597 ms/op
     p(50.0000) =      5.259 ms/op
     p(90.0000) =      6.455 ms/op
     p(95.0000) =      7.258 ms/op
     p(99.0000) =     10.813 ms/op
     p(99.9000) =     22.119 ms/op
     p(99.9900) =     25.500 ms/op
     p(99.9990) =     27.177 ms/op
     p(99.9999) =     27.492 ms/op
    p(100.0000) =     27.492 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   6.471 ± 6.449  ops/ms
ClientPb.existUser                       thrpt       3   7.262 ± 2.142  ops/ms
ClientPb.getUser                         thrpt       3   6.716 ± 1.323  ops/ms
ClientPb.listUser                        thrpt       3   5.950 ± 1.496  ops/ms
ClientPb.createUser                       avgt       3   4.868 ± 0.974   ms/op
ClientPb.existUser                        avgt       3   4.525 ± 1.762   ms/op
ClientPb.getUser                          avgt       3   4.986 ± 4.360   ms/op
ClientPb.listUser                         avgt       3   5.609 ± 1.472   ms/op
ClientPb.createUser                     sample  197125   4.871 ± 0.010   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.831           ms/op
ClientPb.createUser:createUser·p0.50    sample           4.612           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.070           ms/op
ClientPb.createUser:createUser·p0.95    sample           6.824           ms/op
ClientPb.createUser:createUser·p0.99    sample           9.306           ms/op
ClientPb.createUser:createUser·p0.999   sample          24.244           ms/op
ClientPb.createUser:createUser·p0.9999  sample          32.440           ms/op
ClientPb.createUser:createUser·p1.00    sample          35.455           ms/op
ClientPb.existUser                      sample  208438   4.600 ± 0.008   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.720           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.366           ms/op
ClientPb.existUser:existUser·p0.90      sample           5.636           ms/op
ClientPb.existUser:existUser·p0.95      sample           6.398           ms/op
ClientPb.existUser:existUser·p0.99      sample           8.618           ms/op
ClientPb.existUser:existUser·p0.999     sample          15.459           ms/op
ClientPb.existUser:existUser·p0.9999    sample          23.182           ms/op
ClientPb.existUser:existUser·p1.00      sample          25.133           ms/op
ClientPb.getUser                        sample  184343   5.204 ± 0.011   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.958           ms/op
ClientPb.getUser:getUser·p0.50          sample           4.874           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.480           ms/op
ClientPb.getUser:getUser·p0.95          sample           7.676           ms/op
ClientPb.getUser:getUser·p0.99          sample          10.977           ms/op
ClientPb.getUser:getUser·p0.999         sample          18.874           ms/op
ClientPb.getUser:getUser·p0.9999        sample          30.558           ms/op
ClientPb.getUser:getUser·p1.00          sample          32.276           ms/op
ClientPb.listUser                       sample  173988   5.512 ± 0.010   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.597           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.259           ms/op
ClientPb.listUser:listUser·p0.90        sample           6.455           ms/op
ClientPb.listUser:listUser·p0.95        sample           7.258           ms/op
ClientPb.listUser:listUser·p0.99        sample          10.813           ms/op
ClientPb.listUser:listUser·p0.999       sample          22.119           ms/op
ClientPb.listUser:listUser·p0.9999      sample          25.500           ms/op
ClientPb.listUser:listUser·p1.00        sample          27.492           ms/op
