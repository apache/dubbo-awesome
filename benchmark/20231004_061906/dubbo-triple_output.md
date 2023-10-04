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
# Warmup Iteration   1: 2.019 ops/ms
# Warmup Iteration   2: 5.658 ops/ms
# Warmup Iteration   3: 8.351 ops/ms
Iteration   1: 8.945 ops/ms
Iteration   2: 9.153 ops/ms
Iteration   3: 8.957 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.018 ±(99.9%) 2.133 ops/ms [Average]
  (min, avg, max) = (8.945, 9.018, 9.153), stdev = 0.117
  CI (99.9%): [6.885, 11.152] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 2.663 ops/ms
# Warmup Iteration   2: 7.819 ops/ms
# Warmup Iteration   3: 9.268 ops/ms
Iteration   1: 9.641 ops/ms
Iteration   2: 9.426 ops/ms
Iteration   3: 9.752 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.606 ±(99.9%) 3.019 ops/ms [Average]
  (min, avg, max) = (9.426, 9.606, 9.752), stdev = 0.165
  CI (99.9%): [6.588, 12.625] (assumes normal distribution)


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
# Warmup Iteration   1: 3.083 ops/ms
# Warmup Iteration   2: 8.569 ops/ms
# Warmup Iteration   3: 8.968 ops/ms
Iteration   1: 8.958 ops/ms
Iteration   2: 9.229 ops/ms
Iteration   3: 9.298 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.162 ±(99.9%) 3.277 ops/ms [Average]
  (min, avg, max) = (8.958, 9.162, 9.298), stdev = 0.180
  CI (99.9%): [5.885, 12.438] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:56
# Fork: 1 of 1
# Warmup Iteration   1: 2.522 ops/ms
# Warmup Iteration   2: 6.844 ops/ms
# Warmup Iteration   3: 7.622 ops/ms
Iteration   1: 7.541 ops/ms
Iteration   2: 7.691 ops/ms
Iteration   3: 7.777 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.669 ±(99.9%) 2.175 ops/ms [Average]
  (min, avg, max) = (7.541, 7.669, 7.777), stdev = 0.119
  CI (99.9%): [5.494, 9.844] (assumes normal distribution)


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
# Warmup Iteration   1: 10.405 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 3.809 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.836 ±(99.9%) 0.004 ms/op
Iteration   1: 3.515 ±(99.9%) 0.007 ms/op
Iteration   2: 3.537 ±(99.9%) 0.006 ms/op
Iteration   3: 3.545 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.532 ±(99.9%) 0.282 ms/op [Average]
  (min, avg, max) = (3.515, 3.532, 3.545), stdev = 0.015
  CI (99.9%): [3.250, 3.814] (assumes normal distribution)


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
# Warmup Iteration   1: 10.598 ±(99.9%) 0.104 ms/op
# Warmup Iteration   2: 3.709 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.602 ±(99.9%) 0.003 ms/op
Iteration   1: 3.415 ±(99.9%) 0.005 ms/op
Iteration   2: 3.388 ±(99.9%) 0.003 ms/op
Iteration   3: 3.361 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.388 ±(99.9%) 0.492 ms/op [Average]
  (min, avg, max) = (3.361, 3.388, 3.415), stdev = 0.027
  CI (99.9%): [2.896, 3.880] (assumes normal distribution)


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
# Warmup Iteration   1: 11.246 ±(99.9%) 0.067 ms/op
# Warmup Iteration   2: 3.994 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.657 ±(99.9%) 0.007 ms/op
Iteration   1: 3.527 ±(99.9%) 0.005 ms/op
Iteration   2: 3.650 ±(99.9%) 0.005 ms/op
Iteration   3: 3.615 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.597 ±(99.9%) 1.163 ms/op [Average]
  (min, avg, max) = (3.527, 3.597, 3.650), stdev = 0.064
  CI (99.9%): [2.434, 4.761] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 11.415 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 4.615 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.278 ±(99.9%) 0.007 ms/op
Iteration   1: 4.126 ±(99.9%) 0.008 ms/op
Iteration   2: 4.226 ±(99.9%) 0.006 ms/op
Iteration   3: 4.218 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.190 ±(99.9%) 1.014 ms/op [Average]
  (min, avg, max) = (4.126, 4.190, 4.226), stdev = 0.056
  CI (99.9%): [3.175, 5.204] (assumes normal distribution)


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
# Warmup Iteration   1: 10.201 ±(99.9%) 0.135 ms/op
# Warmup Iteration   2: 4.207 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 3.678 ±(99.9%) 0.012 ms/op
Iteration   1: 3.777 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.516 ms/op
                 createUser·p0.50:   3.506 ms/op
                 createUser·p0.90:   4.465 ms/op
                 createUser·p0.95:   6.144 ms/op
                 createUser·p0.99:   7.954 ms/op
                 createUser·p0.999:  11.485 ms/op
                 createUser·p0.9999: 21.830 ms/op
                 createUser·p1.00:   25.526 ms/op

Iteration   2: 3.748 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.153 ms/op
                 createUser·p0.50:   3.596 ms/op
                 createUser·p0.90:   4.334 ms/op
                 createUser·p0.95:   4.719 ms/op
                 createUser·p0.99:   6.838 ms/op
                 createUser·p0.999:  21.223 ms/op
                 createUser·p0.9999: 23.084 ms/op
                 createUser·p1.00:   23.626 ms/op

Iteration   3: 3.545 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.241 ms/op
                 createUser·p0.50:   3.391 ms/op
                 createUser·p0.90:   4.002 ms/op
                 createUser·p0.95:   4.284 ms/op
                 createUser·p0.99:   6.347 ms/op
                 createUser·p0.999:  24.510 ms/op
                 createUser·p0.9999: 28.762 ms/op
                 createUser·p1.00:   30.900 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 260198
  mean =      3.687 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3008 
    [ 2.500,  5.000) = 245239 
    [ 5.000,  7.500) = 9055 
    [ 7.500, 10.000) = 2271 
    [10.000, 12.500) = 216 
    [12.500, 15.000) = 37 
    [15.000, 17.500) = 22 
    [17.500, 20.000) = 72 
    [20.000, 22.500) = 141 
    [22.500, 25.000) = 65 
    [25.000, 27.500) = 47 
    [27.500, 30.000) = 21 
    [30.000, 32.500) = 4 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.153 ms/op
     p(50.0000) =      3.490 ms/op
     p(90.0000) =      4.252 ms/op
     p(95.0000) =      4.809 ms/op
     p(99.0000) =      7.569 ms/op
     p(99.9000) =     20.808 ms/op
     p(99.9900) =     27.492 ms/op
     p(99.9990) =     30.867 ms/op
     p(99.9999) =     30.900 ms/op
    p(100.0000) =     30.900 ms/op


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
# Warmup Iteration   1: 9.644 ±(99.9%) 0.152 ms/op
# Warmup Iteration   2: 3.589 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.414 ±(99.9%) 0.009 ms/op
Iteration   1: 3.448 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.618 ms/op
                 existUser·p0.50:   3.269 ms/op
                 existUser·p0.90:   3.842 ms/op
                 existUser·p0.95:   4.342 ms/op
                 existUser·p0.99:   6.971 ms/op
                 existUser·p0.999:  20.808 ms/op
                 existUser·p0.9999: 23.902 ms/op
                 existUser·p1.00:   26.608 ms/op

Iteration   2: 3.458 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.928 ms/op
                 existUser·p0.50:   3.363 ms/op
                 existUser·p0.90:   3.867 ms/op
                 existUser·p0.95:   4.309 ms/op
                 existUser·p0.99:   6.841 ms/op
                 existUser·p0.999:  21.809 ms/op
                 existUser·p0.9999: 26.165 ms/op
                 existUser·p1.00:   26.542 ms/op

Iteration   3: 3.383 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.634 ms/op
                 existUser·p0.50:   3.322 ms/op
                 existUser·p0.90:   3.670 ms/op
                 existUser·p0.95:   4.125 ms/op
                 existUser·p0.99:   6.676 ms/op
                 existUser·p0.999:  12.656 ms/op
                 existUser·p0.9999: 25.428 ms/op
                 existUser·p1.00:   26.673 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 279818
  mean =      3.429 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12160 
    [ 2.500,  5.000) = 259162 
    [ 5.000,  7.500) = 6820 
    [ 7.500, 10.000) = 742 
    [10.000, 12.500) = 505 
    [12.500, 15.000) = 120 
    [15.000, 17.500) = 38 
    [17.500, 20.000) = 4 
    [20.000, 22.500) = 89 
    [22.500, 25.000) = 121 
    [25.000, 27.500) = 57 

  Percentiles, ms/op:
      p(0.0000) =      0.928 ms/op
     p(50.0000) =      3.322 ms/op
     p(90.0000) =      3.805 ms/op
     p(95.0000) =      4.268 ms/op
     p(99.0000) =      6.865 ms/op
     p(99.9000) =     16.810 ms/op
     p(99.9900) =     25.691 ms/op
     p(99.9990) =     26.555 ms/op
     p(99.9999) =     26.673 ms/op
    p(100.0000) =     26.673 ms/op


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
# Warmup Iteration   1: 9.823 ±(99.9%) 0.134 ms/op
# Warmup Iteration   2: 3.874 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 3.678 ±(99.9%) 0.013 ms/op
Iteration   1: 3.583 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.200 ms/op
                 getUser·p0.50:   3.371 ms/op
                 getUser·p0.90:   4.211 ms/op
                 getUser·p0.95:   5.054 ms/op
                 getUser·p0.99:   6.971 ms/op
                 getUser·p0.999:  18.849 ms/op
                 getUser·p0.9999: 21.372 ms/op
                 getUser·p1.00:   22.577 ms/op

Iteration   2: 3.600 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.511 ms/op
                 getUser·p0.50:   3.408 ms/op
                 getUser·p0.90:   4.059 ms/op
                 getUser·p0.95:   4.743 ms/op
                 getUser·p0.99:   7.135 ms/op
                 getUser·p0.999:  20.709 ms/op
                 getUser·p0.9999: 23.138 ms/op
                 getUser·p1.00:   23.855 ms/op

Iteration   3: 3.680 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   0.782 ms/op
                 getUser·p0.50:   3.527 ms/op
                 getUser·p0.90:   4.162 ms/op
                 getUser·p0.95:   4.669 ms/op
                 getUser·p0.99:   7.209 ms/op
                 getUser·p0.999:  20.152 ms/op
                 getUser·p0.9999: 25.952 ms/op
                 getUser·p1.00:   26.280 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 264910
  mean =      3.621 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6830 
    [ 2.500,  5.000) = 245504 
    [ 5.000,  7.500) = 10579 
    [ 7.500, 10.000) = 1261 
    [10.000, 12.500) = 270 
    [12.500, 15.000) = 104 
    [15.000, 17.500) = 54 
    [17.500, 20.000) = 60 
    [20.000, 22.500) = 169 
    [22.500, 25.000) = 61 
    [25.000, 27.500) = 18 

  Percentiles, ms/op:
      p(0.0000) =      0.782 ms/op
     p(50.0000) =      3.424 ms/op
     p(90.0000) =      4.141 ms/op
     p(95.0000) =      4.932 ms/op
     p(99.0000) =      7.119 ms/op
     p(99.9000) =     19.759 ms/op
     p(99.9900) =     24.429 ms/op
     p(99.9990) =     26.195 ms/op
     p(99.9999) =     26.280 ms/op
    p(100.0000) =     26.280 ms/op


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
# Warmup Iteration   1: 10.772 ±(99.9%) 0.168 ms/op
# Warmup Iteration   2: 4.443 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.233 ±(99.9%) 0.014 ms/op
Iteration   1: 4.213 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.694 ms/op
                 listUser·p0.50:   4.018 ms/op
                 listUser·p0.90:   4.694 ms/op
                 listUser·p0.95:   5.161 ms/op
                 listUser·p0.99:   7.987 ms/op
                 listUser·p0.999:  22.544 ms/op
                 listUser·p0.9999: 30.949 ms/op
                 listUser·p1.00:   31.719 ms/op

Iteration   2: 4.190 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   2.290 ms/op
                 listUser·p0.50:   3.965 ms/op
                 listUser·p0.90:   4.645 ms/op
                 listUser·p0.95:   5.145 ms/op
                 listUser·p0.99:   8.815 ms/op
                 listUser·p0.999:  17.275 ms/op
                 listUser·p0.9999: 22.290 ms/op
                 listUser·p1.00:   23.593 ms/op

Iteration   3: 4.176 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.372 ms/op
                 listUser·p0.50:   4.002 ms/op
                 listUser·p0.90:   4.579 ms/op
                 listUser·p0.95:   5.030 ms/op
                 listUser·p0.99:   8.389 ms/op
                 listUser·p0.999:  15.103 ms/op
                 listUser·p0.9999: 16.974 ms/op
                 listUser·p1.00:   17.629 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 228638
  mean =      4.193 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 36 
    [ 2.500,  5.000) = 215830 
    [ 5.000,  7.500) = 8716 
    [ 7.500, 10.000) = 2926 
    [10.000, 12.500) = 469 
    [12.500, 15.000) = 196 
    [15.000, 17.500) = 277 
    [17.500, 20.000) = 48 
    [20.000, 22.500) = 58 
    [22.500, 25.000) = 49 
    [25.000, 27.500) = 4 
    [27.500, 30.000) = 14 
    [30.000, 32.500) = 15 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.694 ms/op
     p(50.0000) =      3.990 ms/op
     p(90.0000) =      4.637 ms/op
     p(95.0000) =      5.120 ms/op
     p(99.0000) =      8.372 ms/op
     p(99.9000) =     16.810 ms/op
     p(99.9900) =     29.360 ms/op
     p(99.9990) =     31.532 ms/op
     p(99.9999) =     31.719 ms/op
    p(100.0000) =     31.719 ms/op


# Run complete. Total time: 00:13:15

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.018 ± 2.133  ops/ms
ClientPb.existUser                       thrpt       3   9.606 ± 3.019  ops/ms
ClientPb.getUser                         thrpt       3   9.162 ± 3.277  ops/ms
ClientPb.listUser                        thrpt       3   7.669 ± 2.175  ops/ms
ClientPb.createUser                       avgt       3   3.532 ± 0.282   ms/op
ClientPb.existUser                        avgt       3   3.388 ± 0.492   ms/op
ClientPb.getUser                          avgt       3   3.597 ± 1.163   ms/op
ClientPb.listUser                         avgt       3   4.190 ± 1.014   ms/op
ClientPb.createUser                     sample  260198   3.687 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.153           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.490           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.252           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.809           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.569           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.808           ms/op
ClientPb.createUser:createUser·p0.9999  sample          27.492           ms/op
ClientPb.createUser:createUser·p1.00    sample          30.900           ms/op
ClientPb.existUser                      sample  279818   3.429 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.928           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.322           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.805           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.268           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.865           ms/op
ClientPb.existUser:existUser·p0.999     sample          16.810           ms/op
ClientPb.existUser:existUser·p0.9999    sample          25.691           ms/op
ClientPb.existUser:existUser·p1.00      sample          26.673           ms/op
ClientPb.getUser                        sample  264910   3.621 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.782           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.424           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.141           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.932           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.119           ms/op
ClientPb.getUser:getUser·p0.999         sample          19.759           ms/op
ClientPb.getUser:getUser·p0.9999        sample          24.429           ms/op
ClientPb.getUser:getUser·p1.00          sample          26.280           ms/op
ClientPb.listUser                       sample  228638   4.193 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.694           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.990           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.637           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.120           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.372           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.810           ms/op
ClientPb.listUser:listUser·p0.9999      sample          29.360           ms/op
ClientPb.listUser:listUser·p1.00        sample          31.719           ms/op
