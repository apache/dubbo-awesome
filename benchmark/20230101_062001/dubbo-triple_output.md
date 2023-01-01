# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.211 ops/ms
# Warmup Iteration   2: 2.967 ops/ms
# Warmup Iteration   3: 6.239 ops/ms
Iteration   1: 6.477 ops/ms
Iteration   2: 6.645 ops/ms
Iteration   3: 6.631 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  6.584 ±(99.9%) 1.698 ops/ms [Average]
  (min, avg, max) = (6.477, 6.584, 6.645), stdev = 0.093
  CI (99.9%): [4.886, 8.282] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.912 ops/ms
# Warmup Iteration   2: 5.856 ops/ms
# Warmup Iteration   3: 6.861 ops/ms
Iteration   1: 6.967 ops/ms
Iteration   2: 6.942 ops/ms
Iteration   3: 6.909 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.940 ±(99.9%) 0.525 ops/ms [Average]
  (min, avg, max) = (6.909, 6.940, 6.967), stdev = 0.029
  CI (99.9%): [6.415, 7.464] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 1.695 ops/ms
# Warmup Iteration   2: 4.942 ops/ms
# Warmup Iteration   3: 6.350 ops/ms
Iteration   1: 6.453 ops/ms
Iteration   2: 6.581 ops/ms
Iteration   3: 6.678 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  6.571 ±(99.9%) 2.063 ops/ms [Average]
  (min, avg, max) = (6.453, 6.571, 6.678), stdev = 0.113
  CI (99.9%): [4.508, 8.634] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 1.714 ops/ms
# Warmup Iteration   2: 4.488 ops/ms
# Warmup Iteration   3: 5.385 ops/ms
Iteration   1: 5.508 ops/ms
Iteration   2: 5.928 ops/ms
Iteration   3: 5.684 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.707 ±(99.9%) 3.853 ops/ms [Average]
  (min, avg, max) = (5.508, 5.707, 5.928), stdev = 0.211
  CI (99.9%): [1.853, 9.560] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 15.273 ±(99.9%) 0.072 ms/op
# Warmup Iteration   2: 6.045 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 5.047 ±(99.9%) 0.013 ms/op
Iteration   1: 4.747 ±(99.9%) 0.016 ms/op
Iteration   2: 4.931 ±(99.9%) 0.009 ms/op
Iteration   3: 5.017 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.898 ±(99.9%) 2.518 ms/op [Average]
  (min, avg, max) = (4.747, 4.898, 5.017), stdev = 0.138
  CI (99.9%): [2.380, 7.416] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 14.198 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 5.511 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.733 ±(99.9%) 0.012 ms/op
Iteration   1: 4.671 ±(99.9%) 0.010 ms/op
Iteration   2: 4.850 ±(99.9%) 0.013 ms/op
Iteration   3: 4.583 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  4.701 ±(99.9%) 2.478 ms/op [Average]
  (min, avg, max) = (4.583, 4.701, 4.850), stdev = 0.136
  CI (99.9%): [2.223, 7.179] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 14.770 ±(99.9%) 0.071 ms/op
# Warmup Iteration   2: 5.529 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 5.029 ±(99.9%) 0.010 ms/op
Iteration   1: 4.917 ±(99.9%) 0.010 ms/op
Iteration   2: 5.016 ±(99.9%) 0.010 ms/op
Iteration   3: 4.853 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.929 ±(99.9%) 1.502 ms/op [Average]
  (min, avg, max) = (4.853, 4.929, 5.016), stdev = 0.082
  CI (99.9%): [3.426, 6.431] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 19.432 ±(99.9%) 0.069 ms/op
# Warmup Iteration   2: 6.574 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 5.846 ±(99.9%) 0.014 ms/op
Iteration   1: 6.295 ±(99.9%) 0.020 ms/op
Iteration   2: 5.484 ±(99.9%) 0.018 ms/op
Iteration   3: 5.705 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.828 ±(99.9%) 7.650 ms/op [Average]
  (min, avg, max) = (5.484, 5.828, 6.295), stdev = 0.419
  CI (99.9%): [≈ 0, 13.478] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 15.043 ±(99.9%) 0.227 ms/op
# Warmup Iteration   2: 5.694 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 5.495 ±(99.9%) 0.022 ms/op
Iteration   1: 4.916 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   2.204 ms/op
                 createUser·p0.50:   4.637 ms/op
                 createUser·p0.90:   6.038 ms/op
                 createUser·p0.95:   6.930 ms/op
                 createUser·p0.99:   9.355 ms/op
                 createUser·p0.999:  15.734 ms/op
                 createUser·p0.9999: 26.427 ms/op
                 createUser·p1.00:   27.361 ms/op

Iteration   2: 4.673 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.970 ms/op
                 createUser·p0.50:   4.415 ms/op
                 createUser·p0.90:   5.808 ms/op
                 createUser·p0.95:   6.611 ms/op
                 createUser·p0.99:   8.585 ms/op
                 createUser·p0.999:  14.434 ms/op
                 createUser·p0.9999: 30.872 ms/op
                 createUser·p1.00:   31.523 ms/op

Iteration   3: 4.993 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   1.958 ms/op
                 createUser·p0.50:   4.678 ms/op
                 createUser·p0.90:   6.210 ms/op
                 createUser·p0.95:   6.889 ms/op
                 createUser·p0.99:   9.241 ms/op
                 createUser·p0.999:  26.608 ms/op
                 createUser·p0.9999: 32.820 ms/op
                 createUser·p1.00:   33.817 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 197645
  mean =      4.857 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 70 
    [ 2.500,  5.000) = 140814 
    [ 5.000,  7.500) = 50750 
    [ 7.500, 10.000) = 4875 
    [10.000, 12.500) = 698 
    [12.500, 15.000) = 169 
    [15.000, 17.500) = 30 
    [17.500, 20.000) = 5 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 46 
    [25.000, 27.500) = 90 
    [27.500, 30.000) = 44 
    [30.000, 32.500) = 32 
    [32.500, 35.000) = 10 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.958 ms/op
     p(50.0000) =      4.547 ms/op
     p(90.0000) =      6.054 ms/op
     p(95.0000) =      6.791 ms/op
     p(99.0000) =      9.028 ms/op
     p(99.9000) =     24.325 ms/op
     p(99.9900) =     30.973 ms/op
     p(99.9990) =     33.753 ms/op
     p(99.9999) =     33.817 ms/op
    p(100.0000) =     33.817 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 15.002 ±(99.9%) 0.224 ms/op
# Warmup Iteration   2: 5.095 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.686 ±(99.9%) 0.016 ms/op
Iteration   1: 4.635 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   1.907 ms/op
                 existUser·p0.50:   4.399 ms/op
                 existUser·p0.90:   5.652 ms/op
                 existUser·p0.95:   6.529 ms/op
                 existUser·p0.99:   8.503 ms/op
                 existUser·p0.999:  12.714 ms/op
                 existUser·p0.9999: 24.055 ms/op
                 existUser·p1.00:   24.510 ms/op

Iteration   2: 4.742 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   1.999 ms/op
                 existUser·p0.50:   4.465 ms/op
                 existUser·p0.90:   5.693 ms/op
                 existUser·p0.95:   6.627 ms/op
                 existUser·p0.99:   9.601 ms/op
                 existUser·p0.999:  23.598 ms/op
                 existUser·p0.9999: 33.587 ms/op
                 existUser·p1.00:   36.241 ms/op

Iteration   3: 4.844 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   2.095 ms/op
                 existUser·p0.50:   4.514 ms/op
                 existUser·p0.90:   6.054 ms/op
                 existUser·p0.95:   7.070 ms/op
                 existUser·p0.99:   9.781 ms/op
                 existUser·p0.999:  16.515 ms/op
                 existUser·p0.9999: 30.684 ms/op
                 existUser·p1.00:   31.949 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 202407
  mean =      4.739 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 132 
    [ 2.500,  5.000) = 155245 
    [ 5.000,  7.500) = 40814 
    [ 7.500, 10.000) = 4801 
    [10.000, 12.500) = 787 
    [12.500, 15.000) = 277 
    [15.000, 17.500) = 122 
    [17.500, 20.000) = 35 
    [20.000, 22.500) = 50 
    [22.500, 25.000) = 75 
    [25.000, 27.500) = 27 
    [27.500, 30.000) = 20 
    [30.000, 32.500) = 14 
    [32.500, 35.000) = 6 
    [35.000, 37.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.907 ms/op
     p(50.0000) =      4.456 ms/op
     p(90.0000) =      5.808 ms/op
     p(95.0000) =      6.758 ms/op
     p(99.0000) =      9.306 ms/op
     p(99.9000) =     19.673 ms/op
     p(99.9900) =     30.164 ms/op
     p(99.9990) =     35.252 ms/op
     p(99.9999) =     36.241 ms/op
    p(100.0000) =     36.241 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 14.782 ±(99.9%) 0.213 ms/op
# Warmup Iteration   2: 5.764 ±(99.9%) 0.031 ms/op
# Warmup Iteration   3: 4.934 ±(99.9%) 0.017 ms/op
Iteration   1: 4.898 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   2.372 ms/op
                 getUser·p0.50:   4.571 ms/op
                 getUser·p0.90:   5.972 ms/op
                 getUser·p0.95:   7.209 ms/op
                 getUser·p0.99:   10.159 ms/op
                 getUser·p0.999:  17.968 ms/op
                 getUser·p0.9999: 25.428 ms/op
                 getUser·p1.00:   27.623 ms/op

Iteration   2: 5.154 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   2.523 ms/op
                 getUser·p0.50:   4.866 ms/op
                 getUser·p0.90:   6.210 ms/op
                 getUser·p0.95:   7.381 ms/op
                 getUser·p0.99:   9.978 ms/op
                 getUser·p0.999:  23.108 ms/op
                 getUser·p0.9999: 31.403 ms/op
                 getUser·p1.00:   32.408 ms/op

Iteration   3: 5.280 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   1.974 ms/op
                 getUser·p0.50:   4.956 ms/op
                 getUser·p0.90:   6.504 ms/op
                 getUser·p0.95:   7.635 ms/op
                 getUser·p0.99:   10.748 ms/op
                 getUser·p0.999:  26.473 ms/op
                 getUser·p0.9999: 31.685 ms/op
                 getUser·p1.00:   32.965 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 187992
  mean =      5.106 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12 
    [ 2.500,  5.000) = 114802 
    [ 5.000,  7.500) = 64204 
    [ 7.500, 10.000) = 6820 
    [10.000, 12.500) = 1405 
    [12.500, 15.000) = 390 
    [15.000, 17.500) = 138 
    [17.500, 20.000) = 19 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 56 
    [25.000, 27.500) = 37 
    [27.500, 30.000) = 28 
    [30.000, 32.500) = 53 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.974 ms/op
     p(50.0000) =      4.801 ms/op
     p(90.0000) =      6.234 ms/op
     p(95.0000) =      7.397 ms/op
     p(99.0000) =     10.371 ms/op
     p(99.9000) =     20.775 ms/op
     p(99.9900) =     31.300 ms/op
     p(99.9990) =     32.532 ms/op
     p(99.9999) =     32.965 ms/op
    p(100.0000) =     32.965 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 17.681 ±(99.9%) 0.303 ms/op
# Warmup Iteration   2: 6.947 ±(99.9%) 0.041 ms/op
# Warmup Iteration   3: 5.948 ±(99.9%) 0.023 ms/op
Iteration   1: 5.955 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   1.792 ms/op
                 listUser·p0.50:   5.538 ms/op
                 listUser·p0.90:   7.307 ms/op
                 listUser·p0.95:   8.733 ms/op
                 listUser·p0.99:   13.009 ms/op
                 listUser·p0.999:  24.519 ms/op
                 listUser·p0.9999: 26.509 ms/op
                 listUser·p1.00:   27.754 ms/op

Iteration   2: 5.670 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   1.499 ms/op
                 listUser·p0.50:   5.399 ms/op
                 listUser·p0.90:   6.775 ms/op
                 listUser·p0.95:   7.643 ms/op
                 listUser·p0.99:   10.515 ms/op
                 listUser·p0.999:  24.969 ms/op
                 listUser·p0.9999: 29.015 ms/op
                 listUser·p1.00:   30.966 ms/op

Iteration   3: 5.611 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   2.241 ms/op
                 listUser·p0.50:   5.366 ms/op
                 listUser·p0.90:   6.595 ms/op
                 listUser·p0.95:   7.348 ms/op
                 listUser·p0.99:   10.125 ms/op
                 listUser·p0.999:  20.873 ms/op
                 listUser·p0.9999: 23.865 ms/op
                 listUser·p1.00:   25.133 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 167060
  mean =      5.742 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14 
    [ 2.500,  5.000) = 39249 
    [ 5.000,  7.500) = 117312 
    [ 7.500, 10.000) = 7559 
    [10.000, 12.500) = 1918 
    [12.500, 15.000) = 370 
    [15.000, 17.500) = 229 
    [17.500, 20.000) = 99 
    [20.000, 22.500) = 68 
    [22.500, 25.000) = 149 
    [25.000, 27.500) = 82 
    [27.500, 30.000) = 9 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.499 ms/op
     p(50.0000) =      5.431 ms/op
     p(90.0000) =      6.865 ms/op
     p(95.0000) =      7.913 ms/op
     p(99.0000) =     11.174 ms/op
     p(99.9000) =     23.921 ms/op
     p(99.9900) =     27.109 ms/op
     p(99.9990) =     30.394 ms/op
     p(99.9999) =     30.966 ms/op
    p(100.0000) =     30.966 ms/op


# Run complete. Total time: 00:13:14

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   6.584 ± 1.698  ops/ms
ClientPb.existUser                       thrpt       3   6.940 ± 0.525  ops/ms
ClientPb.getUser                         thrpt       3   6.571 ± 2.063  ops/ms
ClientPb.listUser                        thrpt       3   5.707 ± 3.853  ops/ms
ClientPb.createUser                       avgt       3   4.898 ± 2.518   ms/op
ClientPb.existUser                        avgt       3   4.701 ± 2.478   ms/op
ClientPb.getUser                          avgt       3   4.929 ± 1.502   ms/op
ClientPb.listUser                         avgt       3   5.828 ± 7.650   ms/op
ClientPb.createUser                     sample  197645   4.857 ± 0.010   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.958           ms/op
ClientPb.createUser:createUser·p0.50    sample           4.547           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.054           ms/op
ClientPb.createUser:createUser·p0.95    sample           6.791           ms/op
ClientPb.createUser:createUser·p0.99    sample           9.028           ms/op
ClientPb.createUser:createUser·p0.999   sample          24.325           ms/op
ClientPb.createUser:createUser·p0.9999  sample          30.973           ms/op
ClientPb.createUser:createUser·p1.00    sample          33.817           ms/op
ClientPb.existUser                      sample  202407   4.739 ± 0.009   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.907           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.456           ms/op
ClientPb.existUser:existUser·p0.90      sample           5.808           ms/op
ClientPb.existUser:existUser·p0.95      sample           6.758           ms/op
ClientPb.existUser:existUser·p0.99      sample           9.306           ms/op
ClientPb.existUser:existUser·p0.999     sample          19.673           ms/op
ClientPb.existUser:existUser·p0.9999    sample          30.164           ms/op
ClientPb.existUser:existUser·p1.00      sample          36.241           ms/op
ClientPb.getUser                        sample  187992   5.106 ± 0.011   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.974           ms/op
ClientPb.getUser:getUser·p0.50          sample           4.801           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.234           ms/op
ClientPb.getUser:getUser·p0.95          sample           7.397           ms/op
ClientPb.getUser:getUser·p0.99          sample          10.371           ms/op
ClientPb.getUser:getUser·p0.999         sample          20.775           ms/op
ClientPb.getUser:getUser·p0.9999        sample          31.300           ms/op
ClientPb.getUser:getUser·p1.00          sample          32.965           ms/op
ClientPb.listUser                       sample  167060   5.742 ± 0.012   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.499           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.431           ms/op
ClientPb.listUser:listUser·p0.90        sample           6.865           ms/op
ClientPb.listUser:listUser·p0.95        sample           7.913           ms/op
ClientPb.listUser:listUser·p0.99        sample          11.174           ms/op
ClientPb.listUser:listUser·p0.999       sample          23.921           ms/op
ClientPb.listUser:listUser·p0.9999      sample          27.109           ms/op
ClientPb.listUser:listUser·p1.00        sample          30.966           ms/op
