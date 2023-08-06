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
# Warmup Iteration   1: 0.995 ops/ms
# Warmup Iteration   2: 2.163 ops/ms
# Warmup Iteration   3: 5.117 ops/ms
Iteration   1: 5.662 ops/ms
Iteration   2: 5.907 ops/ms
Iteration   3: 6.032 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.867 ±(99.9%) 3.432 ops/ms [Average]
  (min, avg, max) = (5.662, 5.867, 6.032), stdev = 0.188
  CI (99.9%): [2.435, 9.299] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:03
# Fork: 1 of 1
# Warmup Iteration   1: 1.519 ops/ms
# Warmup Iteration   2: 4.944 ops/ms
# Warmup Iteration   3: 5.770 ops/ms
Iteration   1: 5.813 ops/ms
Iteration   2: 6.014 ops/ms
Iteration   3: 5.812 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.880 ±(99.9%) 2.120 ops/ms [Average]
  (min, avg, max) = (5.812, 5.880, 6.014), stdev = 0.116
  CI (99.9%): [3.760, 7.999] (assumes normal distribution)


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
# Warmup Iteration   1: 1.579 ops/ms
# Warmup Iteration   2: 4.920 ops/ms
# Warmup Iteration   3: 5.795 ops/ms
Iteration   1: 5.468 ops/ms
Iteration   2: 5.561 ops/ms
Iteration   3: 5.515 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.514 ±(99.9%) 0.845 ops/ms [Average]
  (min, avg, max) = (5.468, 5.514, 5.561), stdev = 0.046
  CI (99.9%): [4.670, 6.359] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 1.450 ops/ms
# Warmup Iteration   2: 4.042 ops/ms
# Warmup Iteration   3: 5.108 ops/ms
Iteration   1: 4.870 ops/ms
Iteration   2: 5.005 ops/ms
Iteration   3: 4.805 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.894 ±(99.9%) 1.861 ops/ms [Average]
  (min, avg, max) = (4.805, 4.894, 5.005), stdev = 0.102
  CI (99.9%): [3.033, 6.754] (assumes normal distribution)


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
# Warmup Iteration   1: 18.749 ±(99.9%) 0.090 ms/op
# Warmup Iteration   2: 6.777 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 5.948 ±(99.9%) 0.011 ms/op
Iteration   1: 5.700 ±(99.9%) 0.007 ms/op
Iteration   2: 5.547 ±(99.9%) 0.011 ms/op
Iteration   3: 5.400 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.549 ±(99.9%) 2.733 ms/op [Average]
  (min, avg, max) = (5.400, 5.549, 5.700), stdev = 0.150
  CI (99.9%): [2.816, 8.283] (assumes normal distribution)


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
# Warmup Iteration   1: 16.873 ±(99.9%) 0.086 ms/op
# Warmup Iteration   2: 6.448 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 5.578 ±(99.9%) 0.005 ms/op
Iteration   1: 5.526 ±(99.9%) 0.003 ms/op
Iteration   2: 5.200 ±(99.9%) 0.014 ms/op
Iteration   3: 5.377 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.368 ±(99.9%) 2.978 ms/op [Average]
  (min, avg, max) = (5.200, 5.368, 5.526), stdev = 0.163
  CI (99.9%): [2.390, 8.346] (assumes normal distribution)


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
# Warmup Iteration   1: 17.806 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 6.709 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 5.581 ±(99.9%) 0.012 ms/op
Iteration   1: 5.976 ±(99.9%) 0.010 ms/op
Iteration   2: 5.616 ±(99.9%) 0.004 ms/op
Iteration   3: 5.649 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.747 ±(99.9%) 3.627 ms/op [Average]
  (min, avg, max) = (5.616, 5.747, 5.976), stdev = 0.199
  CI (99.9%): [2.120, 9.374] (assumes normal distribution)


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
# Warmup Iteration   1: 20.396 ±(99.9%) 0.079 ms/op
# Warmup Iteration   2: 8.229 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 6.532 ±(99.9%) 0.015 ms/op
Iteration   1: 6.306 ±(99.9%) 0.019 ms/op
Iteration   2: 6.491 ±(99.9%) 0.013 ms/op
Iteration   3: 6.294 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.364 ±(99.9%) 2.019 ms/op [Average]
  (min, avg, max) = (6.294, 6.364, 6.491), stdev = 0.111
  CI (99.9%): [4.344, 8.383] (assumes normal distribution)


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
# Warmup Iteration   1: 17.474 ±(99.9%) 0.285 ms/op
# Warmup Iteration   2: 7.547 ±(99.9%) 0.056 ms/op
# Warmup Iteration   3: 6.213 ±(99.9%) 0.033 ms/op
Iteration   1: 5.637 ±(99.9%) 0.022 ms/op
                 createUser·p0.00:   2.236 ms/op
                 createUser·p0.50:   5.374 ms/op
                 createUser·p0.90:   6.742 ms/op
                 createUser·p0.95:   7.610 ms/op
                 createUser·p0.99:   10.797 ms/op
                 createUser·p0.999:  30.510 ms/op
                 createUser·p0.9999: 35.891 ms/op
                 createUser·p1.00:   36.307 ms/op

Iteration   2: 5.499 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   2.367 ms/op
                 createUser·p0.50:   5.292 ms/op
                 createUser·p0.90:   6.578 ms/op
                 createUser·p0.95:   7.225 ms/op
                 createUser·p0.99:   10.202 ms/op
                 createUser·p0.999:  26.240 ms/op
                 createUser·p0.9999: 28.832 ms/op
                 createUser·p1.00:   29.196 ms/op

Iteration   3: 5.515 ±(99.9%) 0.024 ms/op
                 createUser·p0.00:   1.894 ms/op
                 createUser·p0.50:   5.136 ms/op
                 createUser·p0.90:   6.758 ms/op
                 createUser·p0.95:   8.053 ms/op
                 createUser·p0.99:   11.565 ms/op
                 createUser·p0.999:  26.214 ms/op
                 createUser·p0.9999: 48.326 ms/op
                 createUser·p1.00:   48.628 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 172968
  mean =      5.550 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 62627 
    [ 5.000, 10.000) = 107797 
    [10.000, 15.000) = 2125 
    [15.000, 20.000) = 158 
    [20.000, 25.000) = 35 
    [25.000, 30.000) = 133 
    [30.000, 35.000) = 48 
    [35.000, 40.000) = 16 
    [40.000, 45.000) = 12 

  Percentiles, ms/op:
      p(0.0000) =      1.894 ms/op
     p(50.0000) =      5.259 ms/op
     p(90.0000) =      6.685 ms/op
     p(95.0000) =      7.619 ms/op
     p(99.0000) =     10.895 ms/op
     p(99.9000) =     26.673 ms/op
     p(99.9900) =     45.929 ms/op
     p(99.9990) =     48.580 ms/op
     p(99.9999) =     48.628 ms/op
    p(100.0000) =     48.628 ms/op


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
# Warmup Iteration   1: 18.372 ±(99.9%) 0.313 ms/op
# Warmup Iteration   2: 6.221 ±(99.9%) 0.038 ms/op
# Warmup Iteration   3: 5.527 ±(99.9%) 0.021 ms/op
Iteration   1: 5.395 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   2.552 ms/op
                 existUser·p0.50:   5.161 ms/op
                 existUser·p0.90:   6.316 ms/op
                 existUser·p0.95:   7.225 ms/op
                 existUser·p0.99:   10.420 ms/op
                 existUser·p0.999:  24.624 ms/op
                 existUser·p0.9999: 27.825 ms/op
                 existUser·p1.00:   28.869 ms/op

Iteration   2: 5.233 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   2.417 ms/op
                 existUser·p0.50:   5.022 ms/op
                 existUser·p0.90:   6.119 ms/op
                 existUser·p0.95:   6.898 ms/op
                 existUser·p0.99:   10.027 ms/op
                 existUser·p0.999:  15.707 ms/op
                 existUser·p0.9999: 28.614 ms/op
                 existUser·p1.00:   29.426 ms/op

Iteration   3: 5.344 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   2.413 ms/op
                 existUser·p0.50:   5.038 ms/op
                 existUser·p0.90:   6.463 ms/op
                 existUser·p0.95:   7.610 ms/op
                 existUser·p0.99:   10.633 ms/op
                 existUser·p0.999:  27.139 ms/op
                 existUser·p0.9999: 30.672 ms/op
                 existUser·p1.00:   31.588 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 180159
  mean =      5.323 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13 
    [ 2.500,  5.000) = 79702 
    [ 5.000,  7.500) = 92584 
    [ 7.500, 10.000) = 5750 
    [10.000, 12.500) = 1503 
    [12.500, 15.000) = 307 
    [15.000, 17.500) = 118 
    [17.500, 20.000) = 17 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 58 
    [27.500, 30.000) = 75 
    [30.000, 32.500) = 14 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.413 ms/op
     p(50.0000) =      5.079 ms/op
     p(90.0000) =      6.300 ms/op
     p(95.0000) =      7.217 ms/op
     p(99.0000) =     10.355 ms/op
     p(99.9000) =     19.628 ms/op
     p(99.9900) =     29.589 ms/op
     p(99.9990) =     31.142 ms/op
     p(99.9999) =     31.588 ms/op
    p(100.0000) =     31.588 ms/op


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
# Warmup Iteration   1: 16.683 ±(99.9%) 0.317 ms/op
# Warmup Iteration   2: 6.428 ±(99.9%) 0.041 ms/op
# Warmup Iteration   3: 5.457 ±(99.9%) 0.022 ms/op
Iteration   1: 5.528 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   2.720 ms/op
                 getUser·p0.50:   5.202 ms/op
                 getUser·p0.90:   6.840 ms/op
                 getUser·p0.95:   8.102 ms/op
                 getUser·p0.99:   10.764 ms/op
                 getUser·p0.999:  24.417 ms/op
                 getUser·p0.9999: 27.469 ms/op
                 getUser·p1.00:   28.213 ms/op

Iteration   2: 5.367 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   0.538 ms/op
                 getUser·p0.50:   5.153 ms/op
                 getUser·p0.90:   6.349 ms/op
                 getUser·p0.95:   7.193 ms/op
                 getUser·p0.99:   9.847 ms/op
                 getUser·p0.999:  24.697 ms/op
                 getUser·p0.9999: 27.265 ms/op
                 getUser·p1.00:   28.475 ms/op

Iteration   3: 5.421 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   2.331 ms/op
                 getUser·p0.50:   5.161 ms/op
                 getUser·p0.90:   6.922 ms/op
                 getUser·p0.95:   7.807 ms/op
                 getUser·p0.99:   9.798 ms/op
                 getUser·p0.999:  15.452 ms/op
                 getUser·p0.9999: 26.509 ms/op
                 getUser·p1.00:   27.034 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 176478
  mean =      5.438 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10 
    [ 2.500,  5.000) = 67990 
    [ 5.000,  7.500) = 98409 
    [ 7.500, 10.000) = 8037 
    [10.000, 12.500) = 1499 
    [12.500, 15.000) = 234 
    [15.000, 17.500) = 56 
    [17.500, 20.000) = 56 
    [20.000, 22.500) = 19 
    [22.500, 25.000) = 51 
    [25.000, 27.500) = 109 

  Percentiles, ms/op:
      p(0.0000) =      0.538 ms/op
     p(50.0000) =      5.169 ms/op
     p(90.0000) =      6.693 ms/op
     p(95.0000) =      7.700 ms/op
     p(99.0000) =     10.224 ms/op
     p(99.9000) =     22.284 ms/op
     p(99.9900) =     27.132 ms/op
     p(99.9990) =     28.275 ms/op
     p(99.9999) =     28.475 ms/op
    p(100.0000) =     28.475 ms/op


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
# Warmup Iteration   1: 19.278 ±(99.9%) 0.350 ms/op
# Warmup Iteration   2: 7.854 ±(99.9%) 0.053 ms/op
# Warmup Iteration   3: 6.448 ±(99.9%) 0.027 ms/op
Iteration   1: 6.360 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   3.289 ms/op
                 listUser·p0.50:   5.997 ms/op
                 listUser·p0.90:   7.479 ms/op
                 listUser·p0.95:   8.978 ms/op
                 listUser·p0.99:   13.402 ms/op
                 listUser·p0.999:  28.597 ms/op
                 listUser·p0.9999: 31.030 ms/op
                 listUser·p1.00:   34.472 ms/op

Iteration   2: 6.243 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   2.224 ms/op
                 listUser·p0.50:   5.874 ms/op
                 listUser·p0.90:   7.578 ms/op
                 listUser·p0.95:   8.536 ms/op
                 listUser·p0.99:   11.862 ms/op
                 listUser·p0.999:  27.716 ms/op
                 listUser·p0.9999: 34.595 ms/op
                 listUser·p1.00:   35.127 ms/op

Iteration   3: 6.539 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   2.445 ms/op
                 listUser·p0.50:   6.070 ms/op
                 listUser·p0.90:   8.258 ms/op
                 listUser·p0.95:   9.404 ms/op
                 listUser·p0.99:   13.206 ms/op
                 listUser·p0.999:  25.078 ms/op
                 listUser·p0.9999: 30.474 ms/op
                 listUser·p1.00:   31.392 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 150467
  mean =      6.379 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4 
    [ 2.500,  5.000) = 7065 
    [ 5.000,  7.500) = 125092 
    [ 7.500, 10.000) = 13575 
    [10.000, 12.500) = 2936 
    [12.500, 15.000) = 1010 
    [15.000, 17.500) = 332 
    [17.500, 20.000) = 162 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 93 
    [27.500, 30.000) = 84 
    [30.000, 32.500) = 31 
    [32.500, 35.000) = 31 
    [35.000, 37.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      2.224 ms/op
     p(50.0000) =      5.972 ms/op
     p(90.0000) =      7.791 ms/op
     p(95.0000) =      8.962 ms/op
     p(99.0000) =     12.911 ms/op
     p(99.9000) =     27.492 ms/op
     p(99.9900) =     34.207 ms/op
     p(99.9990) =     35.094 ms/op
     p(99.9999) =     35.127 ms/op
    p(100.0000) =     35.127 ms/op


# Run complete. Total time: 00:13:16

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.867 ± 3.432  ops/ms
ClientPb.existUser                       thrpt       3   5.880 ± 2.120  ops/ms
ClientPb.getUser                         thrpt       3   5.514 ± 0.845  ops/ms
ClientPb.listUser                        thrpt       3   4.894 ± 1.861  ops/ms
ClientPb.createUser                       avgt       3   5.549 ± 2.733   ms/op
ClientPb.existUser                        avgt       3   5.368 ± 2.978   ms/op
ClientPb.getUser                          avgt       3   5.747 ± 3.627   ms/op
ClientPb.listUser                         avgt       3   6.364 ± 2.019   ms/op
ClientPb.createUser                     sample  172968   5.550 ± 0.013   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.894           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.259           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.685           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.619           ms/op
ClientPb.createUser:createUser·p0.99    sample          10.895           ms/op
ClientPb.createUser:createUser·p0.999   sample          26.673           ms/op
ClientPb.createUser:createUser·p0.9999  sample          45.929           ms/op
ClientPb.createUser:createUser·p1.00    sample          48.628           ms/op
ClientPb.existUser                      sample  180159   5.323 ± 0.010   ms/op
ClientPb.existUser:existUser·p0.00      sample           2.413           ms/op
ClientPb.existUser:existUser·p0.50      sample           5.079           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.300           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.217           ms/op
ClientPb.existUser:existUser·p0.99      sample          10.355           ms/op
ClientPb.existUser:existUser·p0.999     sample          19.628           ms/op
ClientPb.existUser:existUser·p0.9999    sample          29.589           ms/op
ClientPb.existUser:existUser·p1.00      sample          31.588           ms/op
ClientPb.getUser                        sample  176478   5.438 ± 0.011   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.538           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.169           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.693           ms/op
ClientPb.getUser:getUser·p0.95          sample           7.700           ms/op
ClientPb.getUser:getUser·p0.99          sample          10.224           ms/op
ClientPb.getUser:getUser·p0.999         sample          22.284           ms/op
ClientPb.getUser:getUser·p0.9999        sample          27.132           ms/op
ClientPb.getUser:getUser·p1.00          sample          28.475           ms/op
ClientPb.listUser                       sample  150467   6.379 ± 0.015   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.224           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.972           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.791           ms/op
ClientPb.listUser:listUser·p0.95        sample           8.962           ms/op
ClientPb.listUser:listUser·p0.99        sample          12.911           ms/op
ClientPb.listUser:listUser·p0.999       sample          27.492           ms/op
ClientPb.listUser:listUser·p0.9999      sample          34.207           ms/op
ClientPb.listUser:listUser·p1.00        sample          35.127           ms/op
