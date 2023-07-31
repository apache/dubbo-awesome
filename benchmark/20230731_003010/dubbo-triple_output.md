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
# Warmup Iteration   1: 1.017 ops/ms
# Warmup Iteration   2: 2.220 ops/ms
# Warmup Iteration   3: 5.212 ops/ms
Iteration   1: 5.437 ops/ms
Iteration   2: 5.750 ops/ms
Iteration   3: 5.792 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.660 ±(99.9%) 3.537 ops/ms [Average]
  (min, avg, max) = (5.437, 5.660, 5.792), stdev = 0.194
  CI (99.9%): [2.123, 9.197] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:05
# Fork: 1 of 1
# Warmup Iteration   1: 1.686 ops/ms
# Warmup Iteration   2: 4.606 ops/ms
# Warmup Iteration   3: 5.977 ops/ms
Iteration   1: 6.204 ops/ms
Iteration   2: 6.036 ops/ms
Iteration   3: 5.921 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.054 ±(99.9%) 2.595 ops/ms [Average]
  (min, avg, max) = (5.921, 6.054, 6.204), stdev = 0.142
  CI (99.9%): [3.459, 8.649] (assumes normal distribution)


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
# Warmup Iteration   1: 1.529 ops/ms
# Warmup Iteration   2: 4.419 ops/ms
# Warmup Iteration   3: 5.568 ops/ms
Iteration   1: 5.640 ops/ms
Iteration   2: 5.658 ops/ms
Iteration   3: 5.573 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.624 ±(99.9%) 0.816 ops/ms [Average]
  (min, avg, max) = (5.573, 5.624, 5.658), stdev = 0.045
  CI (99.9%): [4.808, 6.440] (assumes normal distribution)


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
# Warmup Iteration   1: 1.552 ops/ms
# Warmup Iteration   2: 3.866 ops/ms
# Warmup Iteration   3: 4.938 ops/ms
Iteration   1: 4.738 ops/ms
Iteration   2: 4.951 ops/ms
Iteration   3: 4.858 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.849 ±(99.9%) 1.944 ops/ms [Average]
  (min, avg, max) = (4.738, 4.849, 4.951), stdev = 0.107
  CI (99.9%): [2.905, 6.794] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:52
# Fork: 1 of 1
# Warmup Iteration   1: 18.702 ±(99.9%) 0.095 ms/op
# Warmup Iteration   2: 7.447 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 5.930 ±(99.9%) 0.010 ms/op
Iteration   1: 5.733 ±(99.9%) 0.024 ms/op
Iteration   2: 5.643 ±(99.9%) 0.018 ms/op
Iteration   3: 5.717 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.698 ±(99.9%) 0.876 ms/op [Average]
  (min, avg, max) = (5.643, 5.698, 5.733), stdev = 0.048
  CI (99.9%): [4.822, 6.574] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:45
# Fork: 1 of 1
# Warmup Iteration   1: 16.711 ±(99.9%) 0.084 ms/op
# Warmup Iteration   2: 6.284 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 5.535 ±(99.9%) 0.010 ms/op
Iteration   1: 5.366 ±(99.9%) 0.006 ms/op
Iteration   2: 5.199 ±(99.9%) 0.010 ms/op
Iteration   3: 5.337 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.301 ±(99.9%) 1.627 ms/op [Average]
  (min, avg, max) = (5.199, 5.301, 5.366), stdev = 0.089
  CI (99.9%): [3.674, 6.927] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:38
# Fork: 1 of 1
# Warmup Iteration   1: 17.614 ±(99.9%) 0.073 ms/op
# Warmup Iteration   2: 6.919 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 5.769 ±(99.9%) 0.018 ms/op
Iteration   1: 5.711 ±(99.9%) 0.009 ms/op
Iteration   2: 5.641 ±(99.9%) 0.014 ms/op
Iteration   3: 5.777 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.710 ±(99.9%) 1.246 ms/op [Average]
  (min, avg, max) = (5.641, 5.710, 5.777), stdev = 0.068
  CI (99.9%): [4.464, 6.956] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:32
# Fork: 1 of 1
# Warmup Iteration   1: 21.054 ±(99.9%) 0.088 ms/op
# Warmup Iteration   2: 8.309 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 6.643 ±(99.9%) 0.015 ms/op
Iteration   1: 6.485 ±(99.9%) 0.023 ms/op
Iteration   2: 6.585 ±(99.9%) 0.020 ms/op
Iteration   3: 6.329 ±(99.9%) 0.022 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.466 ±(99.9%) 2.356 ms/op [Average]
  (min, avg, max) = (6.329, 6.466, 6.585), stdev = 0.129
  CI (99.9%): [4.110, 8.822] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:26
# Fork: 1 of 1
# Warmup Iteration   1: 17.011 ±(99.9%) 0.301 ms/op
# Warmup Iteration   2: 7.277 ±(99.9%) 0.045 ms/op
# Warmup Iteration   3: 6.180 ±(99.9%) 0.026 ms/op
Iteration   1: 5.559 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   2.195 ms/op
                 createUser·p0.50:   5.284 ms/op
                 createUser·p0.90:   6.734 ms/op
                 createUser·p0.95:   7.504 ms/op
                 createUser·p0.99:   9.699 ms/op
                 createUser·p0.999:  14.860 ms/op
                 createUser·p0.9999: 28.942 ms/op
                 createUser·p1.00:   29.524 ms/op

Iteration   2: 5.468 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   2.122 ms/op
                 createUser·p0.50:   5.226 ms/op
                 createUser·p0.90:   6.586 ms/op
                 createUser·p0.95:   7.176 ms/op
                 createUser·p0.99:   9.159 ms/op
                 createUser·p0.999:  25.471 ms/op
                 createUser·p0.9999: 30.414 ms/op
                 createUser·p1.00:   31.850 ms/op

Iteration   3: 5.712 ±(99.9%) 0.021 ms/op
                 createUser·p0.00:   1.362 ms/op
                 createUser·p0.50:   5.423 ms/op
                 createUser·p0.90:   6.914 ms/op
                 createUser·p0.95:   7.774 ms/op
                 createUser·p0.99:   10.240 ms/op
                 createUser·p0.999:  30.925 ms/op
                 createUser·p0.9999: 33.260 ms/op
                 createUser·p1.00:   37.224 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 172097
  mean =      5.578 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6 
    [ 2.500,  5.000) = 49548 
    [ 5.000,  7.500) = 114104 
    [ 7.500, 10.000) = 6954 
    [10.000, 12.500) = 949 
    [12.500, 15.000) = 300 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 12 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 6 
    [25.000, 27.500) = 64 
    [27.500, 30.000) = 36 
    [30.000, 32.500) = 61 
    [32.500, 35.000) = 24 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.362 ms/op
     p(50.0000) =      5.308 ms/op
     p(90.0000) =      6.742 ms/op
     p(95.0000) =      7.471 ms/op
     p(99.0000) =      9.699 ms/op
     p(99.9000) =     25.392 ms/op
     p(99.9900) =     32.675 ms/op
     p(99.9990) =     35.382 ms/op
     p(99.9999) =     37.224 ms/op
    p(100.0000) =     37.224 ms/op


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
# Warmup Iteration   1: 15.573 ±(99.9%) 0.239 ms/op
# Warmup Iteration   2: 6.385 ±(99.9%) 0.035 ms/op
# Warmup Iteration   3: 5.717 ±(99.9%) 0.021 ms/op
Iteration   1: 5.406 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   2.486 ms/op
                 existUser·p0.50:   5.136 ms/op
                 existUser·p0.90:   6.636 ms/op
                 existUser·p0.95:   7.274 ms/op
                 existUser·p0.99:   9.208 ms/op
                 existUser·p0.999:  13.989 ms/op
                 existUser·p0.9999: 26.283 ms/op
                 existUser·p1.00:   26.968 ms/op

Iteration   2: 5.276 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   2.753 ms/op
                 existUser·p0.50:   5.014 ms/op
                 existUser·p0.90:   6.218 ms/op
                 existUser·p0.95:   6.832 ms/op
                 existUser·p0.99:   9.523 ms/op
                 existUser·p0.999:  33.838 ms/op
                 existUser·p0.9999: 46.596 ms/op
                 existUser·p1.00:   46.727 ms/op

Iteration   3: 5.547 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   2.224 ms/op
                 existUser·p0.50:   5.308 ms/op
                 existUser·p0.90:   6.717 ms/op
                 existUser·p0.95:   7.643 ms/op
                 existUser·p0.99:   9.945 ms/op
                 existUser·p0.999:  27.701 ms/op
                 existUser·p0.9999: 35.586 ms/op
                 existUser·p1.00:   36.700 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 177499
  mean =      5.407 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 73160 
    [ 5.000, 10.000) = 102873 
    [10.000, 15.000) = 1264 
    [15.000, 20.000) = 40 
    [20.000, 25.000) = 11 
    [25.000, 30.000) = 55 
    [30.000, 35.000) = 48 
    [35.000, 40.000) = 16 
    [40.000, 45.000) = 17 

  Percentiles, ms/op:
      p(0.0000) =      2.224 ms/op
     p(50.0000) =      5.145 ms/op
     p(90.0000) =      6.529 ms/op
     p(95.0000) =      7.258 ms/op
     p(99.0000) =      9.650 ms/op
     p(99.9000) =     18.219 ms/op
     p(99.9900) =     44.433 ms/op
     p(99.9990) =     46.727 ms/op
     p(99.9999) =     46.727 ms/op
    p(100.0000) =     46.727 ms/op


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
# Warmup Iteration   1: 17.795 ±(99.9%) 0.269 ms/op
# Warmup Iteration   2: 6.709 ±(99.9%) 0.037 ms/op
# Warmup Iteration   3: 5.732 ±(99.9%) 0.022 ms/op
Iteration   1: 5.690 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   2.810 ms/op
                 getUser·p0.50:   5.480 ms/op
                 getUser·p0.90:   6.750 ms/op
                 getUser·p0.95:   7.504 ms/op
                 getUser·p0.99:   10.125 ms/op
                 getUser·p0.999:  23.017 ms/op
                 getUser·p0.9999: 28.329 ms/op
                 getUser·p1.00:   29.426 ms/op

Iteration   2: 5.647 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   2.445 ms/op
                 getUser·p0.50:   5.267 ms/op
                 getUser·p0.90:   6.980 ms/op
                 getUser·p0.95:   8.667 ms/op
                 getUser·p0.99:   11.338 ms/op
                 getUser·p0.999:  25.396 ms/op
                 getUser·p0.9999: 30.879 ms/op
                 getUser·p1.00:   32.342 ms/op

Iteration   3: 5.698 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   1.810 ms/op
                 getUser·p0.50:   5.439 ms/op
                 getUser·p0.90:   6.750 ms/op
                 getUser·p0.95:   7.791 ms/op
                 getUser·p0.99:   10.420 ms/op
                 getUser·p0.999:  26.915 ms/op
                 getUser·p0.9999: 30.323 ms/op
                 getUser·p1.00:   30.802 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 168962
  mean =      5.678 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5 
    [ 2.500,  5.000) = 45995 
    [ 5.000,  7.500) = 112520 
    [ 7.500, 10.000) = 8092 
    [10.000, 12.500) = 1589 
    [12.500, 15.000) = 363 
    [15.000, 17.500) = 178 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 17 
    [25.000, 27.500) = 66 
    [27.500, 30.000) = 78 
    [30.000, 32.500) = 28 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.810 ms/op
     p(50.0000) =      5.390 ms/op
     p(90.0000) =      6.816 ms/op
     p(95.0000) =      7.930 ms/op
     p(99.0000) =     10.617 ms/op
     p(99.9000) =     25.068 ms/op
     p(99.9900) =     30.281 ms/op
     p(99.9990) =     32.206 ms/op
     p(99.9999) =     32.342 ms/op
    p(100.0000) =     32.342 ms/op


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
# Warmup Iteration   1: 19.157 ±(99.9%) 0.304 ms/op
# Warmup Iteration   2: 7.578 ±(99.9%) 0.044 ms/op
# Warmup Iteration   3: 6.694 ±(99.9%) 0.026 ms/op
Iteration   1: 6.487 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   3.318 ms/op
                 listUser·p0.50:   6.169 ms/op
                 listUser·p0.90:   7.512 ms/op
                 listUser·p0.95:   8.684 ms/op
                 listUser·p0.99:   11.592 ms/op
                 listUser·p0.999:  29.316 ms/op
                 listUser·p0.9999: 32.805 ms/op
                 listUser·p1.00:   33.554 ms/op

Iteration   2: 6.440 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   2.314 ms/op
                 listUser·p0.50:   6.087 ms/op
                 listUser·p0.90:   7.619 ms/op
                 listUser·p0.95:   8.339 ms/op
                 listUser·p0.99:   11.207 ms/op
                 listUser·p0.999:  30.102 ms/op
                 listUser·p0.9999: 36.180 ms/op
                 listUser·p1.00:   38.273 ms/op

Iteration   3: 6.792 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   2.953 ms/op
                 listUser·p0.50:   6.382 ms/op
                 listUser·p0.90:   8.151 ms/op
                 listUser·p0.95:   9.535 ms/op
                 listUser·p0.99:   13.550 ms/op
                 listUser·p0.999:  22.603 ms/op
                 listUser·p0.9999: 27.828 ms/op
                 listUser·p1.00:   30.704 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 146100
  mean =      6.569 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2 
    [ 2.500,  5.000) = 2571 
    [ 5.000,  7.500) = 125335 
    [ 7.500, 10.000) = 14025 
    [10.000, 12.500) = 2879 
    [12.500, 15.000) = 671 
    [15.000, 17.500) = 255 
    [17.500, 20.000) = 41 
    [20.000, 22.500) = 49 
    [22.500, 25.000) = 38 
    [25.000, 27.500) = 55 
    [27.500, 30.000) = 100 
    [30.000, 32.500) = 47 
    [32.500, 35.000) = 18 
    [35.000, 37.500) = 12 

  Percentiles, ms/op:
      p(0.0000) =      2.314 ms/op
     p(50.0000) =      6.201 ms/op
     p(90.0000) =      7.766 ms/op
     p(95.0000) =      8.831 ms/op
     p(99.0000) =     12.075 ms/op
     p(99.9000) =     28.469 ms/op
     p(99.9900) =     35.022 ms/op
     p(99.9990) =     38.031 ms/op
     p(99.9999) =     38.273 ms/op
    p(100.0000) =     38.273 ms/op


# Run complete. Total time: 00:13:18

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.660 ± 3.537  ops/ms
ClientPb.existUser                       thrpt       3   6.054 ± 2.595  ops/ms
ClientPb.getUser                         thrpt       3   5.624 ± 0.816  ops/ms
ClientPb.listUser                        thrpt       3   4.849 ± 1.944  ops/ms
ClientPb.createUser                       avgt       3   5.698 ± 0.876   ms/op
ClientPb.existUser                        avgt       3   5.301 ± 1.627   ms/op
ClientPb.getUser                          avgt       3   5.710 ± 1.246   ms/op
ClientPb.listUser                         avgt       3   6.466 ± 2.356   ms/op
ClientPb.createUser                     sample  172097   5.578 ± 0.011   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.362           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.308           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.742           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.471           ms/op
ClientPb.createUser:createUser·p0.99    sample           9.699           ms/op
ClientPb.createUser:createUser·p0.999   sample          25.392           ms/op
ClientPb.createUser:createUser·p0.9999  sample          32.675           ms/op
ClientPb.createUser:createUser·p1.00    sample          37.224           ms/op
ClientPb.existUser                      sample  177499   5.407 ± 0.011   ms/op
ClientPb.existUser:existUser·p0.00      sample           2.224           ms/op
ClientPb.existUser:existUser·p0.50      sample           5.145           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.529           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.258           ms/op
ClientPb.existUser:existUser·p0.99      sample           9.650           ms/op
ClientPb.existUser:existUser·p0.999     sample          18.219           ms/op
ClientPb.existUser:existUser·p0.9999    sample          44.433           ms/op
ClientPb.existUser:existUser·p1.00      sample          46.727           ms/op
ClientPb.getUser                        sample  168962   5.678 ± 0.011   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.810           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.390           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.816           ms/op
ClientPb.getUser:getUser·p0.95          sample           7.930           ms/op
ClientPb.getUser:getUser·p0.99          sample          10.617           ms/op
ClientPb.getUser:getUser·p0.999         sample          25.068           ms/op
ClientPb.getUser:getUser·p0.9999        sample          30.281           ms/op
ClientPb.getUser:getUser·p1.00          sample          32.342           ms/op
ClientPb.listUser                       sample  146100   6.569 ± 0.014   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.314           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.201           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.766           ms/op
ClientPb.listUser:listUser·p0.95        sample           8.831           ms/op
ClientPb.listUser:listUser·p0.99        sample          12.075           ms/op
ClientPb.listUser:listUser·p0.999       sample          28.469           ms/op
ClientPb.listUser:listUser·p0.9999      sample          35.022           ms/op
ClientPb.listUser:listUser·p1.00        sample          38.273           ms/op
