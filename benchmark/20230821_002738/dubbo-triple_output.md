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
# Warmup Iteration   1: 1.165 ops/ms
# Warmup Iteration   2: 2.411 ops/ms
# Warmup Iteration   3: 5.114 ops/ms
Iteration   1: 5.419 ops/ms
Iteration   2: 5.575 ops/ms
Iteration   3: 5.832 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.609 ±(99.9%) 3.804 ops/ms [Average]
  (min, avg, max) = (5.419, 5.609, 5.832), stdev = 0.208
  CI (99.9%): [1.805, 9.412] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 1.297 ops/ms
# Warmup Iteration   2: 4.617 ops/ms
# Warmup Iteration   3: 5.709 ops/ms
Iteration   1: 5.955 ops/ms
Iteration   2: 6.182 ops/ms
Iteration   3: 5.896 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.011 ±(99.9%) 2.756 ops/ms [Average]
  (min, avg, max) = (5.896, 6.011, 6.182), stdev = 0.151
  CI (99.9%): [3.255, 8.767] (assumes normal distribution)


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
# Warmup Iteration   1: 1.464 ops/ms
# Warmup Iteration   2: 4.805 ops/ms
# Warmup Iteration   3: 5.836 ops/ms
Iteration   1: 5.813 ops/ms
Iteration   2: 5.941 ops/ms
Iteration   3: 5.861 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.872 ±(99.9%) 1.179 ops/ms [Average]
  (min, avg, max) = (5.813, 5.872, 5.941), stdev = 0.065
  CI (99.9%): [4.693, 7.050] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 1.472 ops/ms
# Warmup Iteration   2: 3.769 ops/ms
# Warmup Iteration   3: 4.648 ops/ms
Iteration   1: 4.568 ops/ms
Iteration   2: 5.009 ops/ms
Iteration   3: 5.017 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.865 ±(99.9%) 4.688 ops/ms [Average]
  (min, avg, max) = (4.568, 4.865, 5.017), stdev = 0.257
  CI (99.9%): [0.176, 9.553] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 17.014 ±(99.9%) 0.070 ms/op
# Warmup Iteration   2: 8.495 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 5.637 ±(99.9%) 0.015 ms/op
Iteration   1: 6.027 ±(99.9%) 0.011 ms/op
Iteration   2: 5.679 ±(99.9%) 0.016 ms/op
Iteration   3: 5.945 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.883 ±(99.9%) 3.315 ms/op [Average]
  (min, avg, max) = (5.679, 5.883, 6.027), stdev = 0.182
  CI (99.9%): [2.569, 9.198] (assumes normal distribution)


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
# Warmup Iteration   1: 17.485 ±(99.9%) 0.067 ms/op
# Warmup Iteration   2: 6.620 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 5.518 ±(99.9%) 0.011 ms/op
Iteration   1: 5.758 ±(99.9%) 0.009 ms/op
Iteration   2: 5.631 ±(99.9%) 0.015 ms/op
Iteration   3: 5.444 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.611 ±(99.9%) 2.884 ms/op [Average]
  (min, avg, max) = (5.444, 5.611, 5.758), stdev = 0.158
  CI (99.9%): [2.726, 8.495] (assumes normal distribution)


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
# Warmup Iteration   1: 18.851 ±(99.9%) 0.087 ms/op
# Warmup Iteration   2: 6.504 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 5.547 ±(99.9%) 0.014 ms/op
Iteration   1: 5.653 ±(99.9%) 0.008 ms/op
Iteration   2: 5.874 ±(99.9%) 0.008 ms/op
Iteration   3: 5.510 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.679 ±(99.9%) 3.352 ms/op [Average]
  (min, avg, max) = (5.510, 5.679, 5.874), stdev = 0.184
  CI (99.9%): [2.327, 9.031] (assumes normal distribution)


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
# Warmup Iteration   1: 18.252 ±(99.9%) 0.077 ms/op
# Warmup Iteration   2: 7.868 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 6.687 ±(99.9%) 0.009 ms/op
Iteration   1: 6.557 ±(99.9%) 0.017 ms/op
Iteration   2: 6.329 ±(99.9%) 0.016 ms/op
Iteration   3: 6.388 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.424 ±(99.9%) 2.160 ms/op [Average]
  (min, avg, max) = (6.329, 6.424, 6.557), stdev = 0.118
  CI (99.9%): [4.264, 8.584] (assumes normal distribution)


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
# Warmup Iteration   1: 17.025 ±(99.9%) 0.276 ms/op
# Warmup Iteration   2: 7.778 ±(99.9%) 0.060 ms/op
# Warmup Iteration   3: 6.384 ±(99.9%) 0.030 ms/op
Iteration   1: 5.809 ±(99.9%) 0.022 ms/op
                 createUser·p0.00:   2.601 ms/op
                 createUser·p0.50:   5.464 ms/op
                 createUser·p0.90:   7.184 ms/op
                 createUser·p0.95:   8.536 ms/op
                 createUser·p0.99:   11.943 ms/op
                 createUser·p0.999:  23.160 ms/op
                 createUser·p0.9999: 26.525 ms/op
                 createUser·p1.00:   28.770 ms/op

Iteration   2: 5.710 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   1.321 ms/op
                 createUser·p0.50:   5.374 ms/op
                 createUser·p0.90:   7.029 ms/op
                 createUser·p0.95:   8.159 ms/op
                 createUser·p0.99:   11.747 ms/op
                 createUser·p0.999:  15.908 ms/op
                 createUser·p0.9999: 30.618 ms/op
                 createUser·p1.00:   31.850 ms/op

Iteration   3: 5.846 ±(99.9%) 0.028 ms/op
                 createUser·p0.00:   1.608 ms/op
                 createUser·p0.50:   5.513 ms/op
                 createUser·p0.90:   7.119 ms/op
                 createUser·p0.95:   8.356 ms/op
                 createUser·p0.99:   12.796 ms/op
                 createUser·p0.999:  27.575 ms/op
                 createUser·p0.9999: 63.342 ms/op
                 createUser·p1.00:   63.439 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 165875
  mean =      5.788 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 45320 
    [ 5.000, 10.000) = 116909 
    [10.000, 15.000) = 3132 
    [15.000, 20.000) = 329 
    [20.000, 25.000) = 61 
    [25.000, 30.000) = 75 
    [30.000, 35.000) = 17 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 2 
    [45.000, 50.000) = 16 
    [50.000, 55.000) = 0 
    [55.000, 60.000) = 6 
    [60.000, 65.000) = 8 

  Percentiles, ms/op:
      p(0.0000) =      1.321 ms/op
     p(50.0000) =      5.448 ms/op
     p(90.0000) =      7.111 ms/op
     p(95.0000) =      8.348 ms/op
     p(99.0000) =     12.108 ms/op
     p(99.9000) =     23.638 ms/op
     p(99.9900) =     48.239 ms/op
     p(99.9990) =     63.439 ms/op
     p(99.9999) =     63.439 ms/op
    p(100.0000) =     63.439 ms/op


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
# Warmup Iteration   1: 16.294 ±(99.9%) 0.267 ms/op
# Warmup Iteration   2: 5.942 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 5.480 ±(99.9%) 0.020 ms/op
Iteration   1: 5.343 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   2.396 ms/op
                 existUser·p0.50:   4.989 ms/op
                 existUser·p0.90:   6.636 ms/op
                 existUser·p0.95:   7.692 ms/op
                 existUser·p0.99:   10.617 ms/op
                 existUser·p0.999:  25.906 ms/op
                 existUser·p0.9999: 33.968 ms/op
                 existUser·p1.00:   35.586 ms/op

Iteration   2: 5.533 ±(99.9%) 0.024 ms/op
                 existUser·p0.00:   2.335 ms/op
                 existUser·p0.50:   5.038 ms/op
                 existUser·p0.90:   7.356 ms/op
                 existUser·p0.95:   8.765 ms/op
                 existUser·p0.99:   12.239 ms/op
                 existUser·p0.999:  26.180 ms/op
                 existUser·p0.9999: 30.388 ms/op
                 existUser·p1.00:   31.687 ms/op

Iteration   3: 5.258 ±(99.9%) 0.021 ms/op
                 existUser·p0.00:   1.829 ms/op
                 existUser·p0.50:   4.923 ms/op
                 existUser·p0.90:   6.431 ms/op
                 existUser·p0.95:   7.512 ms/op
                 existUser·p0.99:   10.928 ms/op
                 existUser·p0.999:  28.882 ms/op
                 existUser·p0.9999: 33.811 ms/op
                 existUser·p1.00:   35.324 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 178479
  mean =      5.376 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 31 
    [ 2.500,  5.000) = 91615 
    [ 5.000,  7.500) = 75000 
    [ 7.500, 10.000) = 8847 
    [10.000, 12.500) = 1761 
    [12.500, 15.000) = 650 
    [15.000, 17.500) = 294 
    [17.500, 20.000) = 65 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 6 
    [25.000, 27.500) = 29 
    [27.500, 30.000) = 84 
    [30.000, 32.500) = 47 
    [32.500, 35.000) = 26 
    [35.000, 37.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      1.829 ms/op
     p(50.0000) =      4.981 ms/op
     p(90.0000) =      6.734 ms/op
     p(95.0000) =      8.053 ms/op
     p(99.0000) =     11.534 ms/op
     p(99.9000) =     26.167 ms/op
     p(99.9900) =     33.564 ms/op
     p(99.9990) =     35.535 ms/op
     p(99.9999) =     35.586 ms/op
    p(100.0000) =     35.586 ms/op


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
# Warmup Iteration   1: 19.088 ±(99.9%) 0.313 ms/op
# Warmup Iteration   2: 7.084 ±(99.9%) 0.053 ms/op
# Warmup Iteration   3: 5.700 ±(99.9%) 0.024 ms/op
Iteration   1: 5.942 ±(99.9%) 0.029 ms/op
                 getUser·p0.00:   2.028 ms/op
                 getUser·p0.50:   5.341 ms/op
                 getUser·p0.90:   7.856 ms/op
                 getUser·p0.95:   9.634 ms/op
                 getUser·p0.99:   15.024 ms/op
                 getUser·p0.999:  23.724 ms/op
                 getUser·p0.9999: 30.514 ms/op
                 getUser·p1.00:   30.736 ms/op

Iteration   2: 5.765 ±(99.9%) 0.023 ms/op
                 getUser·p0.00:   1.823 ms/op
                 getUser·p0.50:   5.341 ms/op
                 getUser·p0.90:   7.291 ms/op
                 getUser·p0.95:   8.749 ms/op
                 getUser·p0.99:   11.843 ms/op
                 getUser·p0.999:  27.492 ms/op
                 getUser·p0.9999: 31.505 ms/op
                 getUser·p1.00:   32.473 ms/op

Iteration   3: 5.673 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   2.580 ms/op
                 getUser·p0.50:   5.300 ms/op
                 getUser·p0.90:   7.070 ms/op
                 getUser·p0.95:   8.094 ms/op
                 getUser·p0.99:   11.076 ms/op
                 getUser·p0.999:  30.048 ms/op
                 getUser·p0.9999: 35.724 ms/op
                 getUser·p1.00:   36.110 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 165752
  mean =      5.791 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3 
    [ 2.500,  5.000) = 47421 
    [ 5.000,  7.500) = 102831 
    [ 7.500, 10.000) = 10986 
    [10.000, 12.500) = 2616 
    [12.500, 15.000) = 1035 
    [15.000, 17.500) = 497 
    [17.500, 20.000) = 123 
    [20.000, 22.500) = 36 
    [22.500, 25.000) = 39 
    [25.000, 27.500) = 23 
    [27.500, 30.000) = 49 
    [30.000, 32.500) = 53 
    [32.500, 35.000) = 25 
    [35.000, 37.500) = 15 

  Percentiles, ms/op:
      p(0.0000) =      1.823 ms/op
     p(50.0000) =      5.325 ms/op
     p(90.0000) =      7.381 ms/op
     p(95.0000) =      8.765 ms/op
     p(99.0000) =     12.927 ms/op
     p(99.9000) =     25.048 ms/op
     p(99.9900) =     34.996 ms/op
     p(99.9990) =     36.024 ms/op
     p(99.9999) =     36.110 ms/op
    p(100.0000) =     36.110 ms/op


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
# Warmup Iteration   1: 22.105 ±(99.9%) 0.414 ms/op
# Warmup Iteration   2: 8.660 ±(99.9%) 0.061 ms/op
# Warmup Iteration   3: 6.826 ±(99.9%) 0.028 ms/op
Iteration   1: 7.149 ±(99.9%) 0.029 ms/op
                 listUser·p0.00:   2.038 ms/op
                 listUser·p0.50:   6.636 ms/op
                 listUser·p0.90:   9.454 ms/op
                 listUser·p0.95:   10.682 ms/op
                 listUser·p0.99:   13.468 ms/op
                 listUser·p0.999:  25.141 ms/op
                 listUser·p0.9999: 29.608 ms/op
                 listUser·p1.00:   31.261 ms/op

Iteration   2: 6.446 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   2.949 ms/op
                 listUser·p0.50:   6.078 ms/op
                 listUser·p0.90:   7.782 ms/op
                 listUser·p0.95:   8.978 ms/op
                 listUser·p0.99:   12.252 ms/op
                 listUser·p0.999:  27.341 ms/op
                 listUser·p0.9999: 31.328 ms/op
                 listUser·p1.00:   32.670 ms/op

Iteration   3: 6.715 ±(99.9%) 0.029 ms/op
                 listUser·p0.00:   2.785 ms/op
                 listUser·p0.50:   6.201 ms/op
                 listUser·p0.90:   8.487 ms/op
                 listUser·p0.95:   10.011 ms/op
                 listUser·p0.99:   14.314 ms/op
                 listUser·p0.999:  27.406 ms/op
                 listUser·p0.9999: 30.162 ms/op
                 listUser·p1.00:   31.195 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 141997
  mean =      6.758 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5 
    [ 2.500,  5.000) = 3586 
    [ 5.000,  7.500) = 111946 
    [ 7.500, 10.000) = 19135 
    [10.000, 12.500) = 5175 
    [12.500, 15.000) = 1277 
    [15.000, 17.500) = 414 
    [17.500, 20.000) = 139 
    [20.000, 22.500) = 53 
    [22.500, 25.000) = 44 
    [25.000, 27.500) = 108 
    [27.500, 30.000) = 93 
    [30.000, 32.500) = 21 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.038 ms/op
     p(50.0000) =      6.283 ms/op
     p(90.0000) =      8.585 ms/op
     p(95.0000) =     10.060 ms/op
     p(99.0000) =     13.369 ms/op
     p(99.9000) =     27.165 ms/op
     p(99.9900) =     30.422 ms/op
     p(99.9990) =     32.505 ms/op
     p(99.9999) =     32.670 ms/op
    p(100.0000) =     32.670 ms/op


# Run complete. Total time: 00:13:16

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.609 ± 3.804  ops/ms
ClientPb.existUser                       thrpt       3   6.011 ± 2.756  ops/ms
ClientPb.getUser                         thrpt       3   5.872 ± 1.179  ops/ms
ClientPb.listUser                        thrpt       3   4.865 ± 4.688  ops/ms
ClientPb.createUser                       avgt       3   5.883 ± 3.315   ms/op
ClientPb.existUser                        avgt       3   5.611 ± 2.884   ms/op
ClientPb.getUser                          avgt       3   5.679 ± 3.352   ms/op
ClientPb.listUser                         avgt       3   6.424 ± 2.160   ms/op
ClientPb.createUser                     sample  165875   5.788 ± 0.014   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.321           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.448           ms/op
ClientPb.createUser:createUser·p0.90    sample           7.111           ms/op
ClientPb.createUser:createUser·p0.95    sample           8.348           ms/op
ClientPb.createUser:createUser·p0.99    sample          12.108           ms/op
ClientPb.createUser:createUser·p0.999   sample          23.638           ms/op
ClientPb.createUser:createUser·p0.9999  sample          48.239           ms/op
ClientPb.createUser:createUser·p1.00    sample          63.439           ms/op
ClientPb.existUser                      sample  178479   5.376 ± 0.013   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.829           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.981           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.734           ms/op
ClientPb.existUser:existUser·p0.95      sample           8.053           ms/op
ClientPb.existUser:existUser·p0.99      sample          11.534           ms/op
ClientPb.existUser:existUser·p0.999     sample          26.167           ms/op
ClientPb.existUser:existUser·p0.9999    sample          33.564           ms/op
ClientPb.existUser:existUser·p1.00      sample          35.586           ms/op
ClientPb.getUser                        sample  165752   5.791 ± 0.014   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.823           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.325           ms/op
ClientPb.getUser:getUser·p0.90          sample           7.381           ms/op
ClientPb.getUser:getUser·p0.95          sample           8.765           ms/op
ClientPb.getUser:getUser·p0.99          sample          12.927           ms/op
ClientPb.getUser:getUser·p0.999         sample          25.048           ms/op
ClientPb.getUser:getUser·p0.9999        sample          34.996           ms/op
ClientPb.getUser:getUser·p1.00          sample          36.110           ms/op
ClientPb.listUser                       sample  141997   6.758 ± 0.016   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.038           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.283           ms/op
ClientPb.listUser:listUser·p0.90        sample           8.585           ms/op
ClientPb.listUser:listUser·p0.95        sample          10.060           ms/op
ClientPb.listUser:listUser·p0.99        sample          13.369           ms/op
ClientPb.listUser:listUser·p0.999       sample          27.165           ms/op
ClientPb.listUser:listUser·p0.9999      sample          30.422           ms/op
ClientPb.listUser:listUser·p1.00        sample          32.670           ms/op
