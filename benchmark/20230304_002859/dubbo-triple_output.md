# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.585 ops/ms
# Warmup Iteration   2: 3.588 ops/ms
# Warmup Iteration   3: 7.501 ops/ms
Iteration   1: 7.398 ops/ms
Iteration   2: 8.156 ops/ms
Iteration   3: 7.580 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.711 ±(99.9%) 7.218 ops/ms [Average]
  (min, avg, max) = (7.398, 7.711, 8.156), stdev = 0.396
  CI (99.9%): [0.493, 14.929] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:11
# Fork: 1 of 1
# Warmup Iteration   1: 2.159 ops/ms
# Warmup Iteration   2: 6.942 ops/ms
# Warmup Iteration   3: 7.695 ops/ms
Iteration   1: 8.427 ops/ms
Iteration   2: 8.430 ops/ms
Iteration   3: 8.714 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.524 ±(99.9%) 3.012 ops/ms [Average]
  (min, avg, max) = (8.427, 8.524, 8.714), stdev = 0.165
  CI (99.9%): [5.512, 11.536] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:59
# Fork: 1 of 1
# Warmup Iteration   1: 2.210 ops/ms
# Warmup Iteration   2: 6.849 ops/ms
# Warmup Iteration   3: 7.481 ops/ms
Iteration   1: 7.666 ops/ms
Iteration   2: 8.103 ops/ms
Iteration   3: 8.239 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.003 ±(99.9%) 5.466 ops/ms [Average]
  (min, avg, max) = (7.666, 8.003, 8.239), stdev = 0.300
  CI (99.9%): [2.537, 13.468] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 2.160 ops/ms
# Warmup Iteration   2: 5.823 ops/ms
# Warmup Iteration   3: 6.583 ops/ms
Iteration   1: 6.906 ops/ms
Iteration   2: 6.843 ops/ms
Iteration   3: 6.847 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.865 ±(99.9%) 0.643 ops/ms [Average]
  (min, avg, max) = (6.843, 6.865, 6.906), stdev = 0.035
  CI (99.9%): [6.222, 7.508] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:49
# Fork: 1 of 1
# Warmup Iteration   1: 13.354 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 4.968 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 4.288 ±(99.9%) 0.006 ms/op
Iteration   1: 3.912 ±(99.9%) 0.013 ms/op
Iteration   2: 3.911 ±(99.9%) 0.007 ms/op
Iteration   3: 3.985 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.936 ±(99.9%) 0.770 ms/op [Average]
  (min, avg, max) = (3.911, 3.936, 3.985), stdev = 0.042
  CI (99.9%): [3.166, 4.706] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:43
# Fork: 1 of 1
# Warmup Iteration   1: 10.235 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 4.688 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.974 ±(99.9%) 0.004 ms/op
Iteration   1: 3.819 ±(99.9%) 0.011 ms/op
Iteration   2: 3.906 ±(99.9%) 0.006 ms/op
Iteration   3: 3.783 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.836 ±(99.9%) 1.153 ms/op [Average]
  (min, avg, max) = (3.783, 3.836, 3.906), stdev = 0.063
  CI (99.9%): [2.683, 4.989] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:37
# Fork: 1 of 1
# Warmup Iteration   1: 12.485 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 4.612 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.125 ±(99.9%) 0.008 ms/op
Iteration   1: 3.945 ±(99.9%) 0.007 ms/op
Iteration   2: 3.958 ±(99.9%) 0.005 ms/op
Iteration   3: 4.067 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.990 ±(99.9%) 1.221 ms/op [Average]
  (min, avg, max) = (3.945, 3.990, 4.067), stdev = 0.067
  CI (99.9%): [2.769, 5.211] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:31
# Fork: 1 of 1
# Warmup Iteration   1: 14.526 ±(99.9%) 0.071 ms/op
# Warmup Iteration   2: 5.003 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 4.949 ±(99.9%) 0.007 ms/op
Iteration   1: 4.650 ±(99.9%) 0.009 ms/op
Iteration   2: 4.538 ±(99.9%) 0.010 ms/op
Iteration   3: 4.451 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.546 ±(99.9%) 1.814 ms/op [Average]
  (min, avg, max) = (4.451, 4.546, 4.650), stdev = 0.099
  CI (99.9%): [2.732, 6.360] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 13.316 ±(99.9%) 0.175 ms/op
# Warmup Iteration   2: 5.065 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 4.419 ±(99.9%) 0.019 ms/op
Iteration   1: 3.979 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.851 ms/op
                 createUser·p0.50:   3.830 ms/op
                 createUser·p0.90:   4.473 ms/op
                 createUser·p0.95:   4.874 ms/op
                 createUser·p0.99:   7.250 ms/op
                 createUser·p0.999:  24.281 ms/op
                 createUser·p0.9999: 30.342 ms/op
                 createUser·p1.00:   31.293 ms/op

Iteration   2: 4.119 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   2.249 ms/op
                 createUser·p0.50:   3.953 ms/op
                 createUser·p0.90:   5.046 ms/op
                 createUser·p0.95:   5.407 ms/op
                 createUser·p0.99:   6.914 ms/op
                 createUser·p0.999:  10.523 ms/op
                 createUser·p0.9999: 32.513 ms/op
                 createUser·p1.00:   34.603 ms/op

Iteration   3: 4.104 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.892 ms/op
                 createUser·p0.50:   3.912 ms/op
                 createUser·p0.90:   4.719 ms/op
                 createUser·p0.95:   5.161 ms/op
                 createUser·p0.99:   7.658 ms/op
                 createUser·p0.999:  28.448 ms/op
                 createUser·p0.9999: 32.705 ms/op
                 createUser·p1.00:   34.537 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 236074
  mean =      4.066 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 286 
    [ 2.500,  5.000) = 219491 
    [ 5.000,  7.500) = 14195 
    [ 7.500, 10.000) = 1642 
    [10.000, 12.500) = 150 
    [12.500, 15.000) = 53 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 67 
    [27.500, 30.000) = 56 
    [30.000, 32.500) = 85 
    [32.500, 35.000) = 19 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.851 ms/op
     p(50.0000) =      3.908 ms/op
     p(90.0000) =      4.710 ms/op
     p(95.0000) =      5.259 ms/op
     p(99.0000) =      7.234 ms/op
     p(99.9000) =     24.576 ms/op
     p(99.9900) =     32.375 ms/op
     p(99.9990) =     34.537 ms/op
     p(99.9999) =     34.603 ms/op
    p(100.0000) =     34.603 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 10.899 ±(99.9%) 0.152 ms/op
# Warmup Iteration   2: 4.317 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.917 ±(99.9%) 0.012 ms/op
Iteration   1: 3.752 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.931 ms/op
                 existUser·p0.50:   3.617 ms/op
                 existUser·p0.90:   4.137 ms/op
                 existUser·p0.95:   4.415 ms/op
                 existUser·p0.99:   6.308 ms/op
                 existUser·p0.999:  23.617 ms/op
                 existUser·p0.9999: 26.932 ms/op
                 existUser·p1.00:   28.836 ms/op

Iteration   2: 3.951 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.831 ms/op
                 existUser·p0.50:   3.805 ms/op
                 existUser·p0.90:   4.547 ms/op
                 existUser·p0.95:   4.907 ms/op
                 existUser·p0.99:   6.767 ms/op
                 existUser·p0.999:  19.366 ms/op
                 existUser·p0.9999: 27.456 ms/op
                 existUser·p1.00:   28.180 ms/op

Iteration   3: 3.847 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.657 ms/op
                 existUser·p0.50:   3.674 ms/op
                 existUser·p0.90:   4.268 ms/op
                 existUser·p0.95:   4.932 ms/op
                 existUser·p0.99:   6.829 ms/op
                 existUser·p0.999:  17.990 ms/op
                 existUser·p0.9999: 30.357 ms/op
                 existUser·p1.00:   31.687 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 249351
  mean =      3.848 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 333 
    [ 2.500,  5.000) = 239451 
    [ 5.000,  7.500) = 8099 
    [ 7.500, 10.000) = 900 
    [10.000, 12.500) = 198 
    [12.500, 15.000) = 72 
    [15.000, 17.500) = 5 
    [17.500, 20.000) = 65 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 64 
    [25.000, 27.500) = 88 
    [27.500, 30.000) = 61 
    [30.000, 32.500) = 11 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.931 ms/op
     p(50.0000) =      3.690 ms/op
     p(90.0000) =      4.334 ms/op
     p(95.0000) =      4.760 ms/op
     p(99.0000) =      6.578 ms/op
     p(99.9000) =     19.256 ms/op
     p(99.9900) =     29.198 ms/op
     p(99.9990) =     31.670 ms/op
     p(99.9999) =     31.687 ms/op
    p(100.0000) =     31.687 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 13.235 ±(99.9%) 0.181 ms/op
# Warmup Iteration   2: 4.467 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.144 ±(99.9%) 0.014 ms/op
Iteration   1: 3.992 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.188 ms/op
                 getUser·p0.50:   3.731 ms/op
                 getUser·p0.90:   4.366 ms/op
                 getUser·p0.95:   5.284 ms/op
                 getUser·p0.99:   8.733 ms/op
                 getUser·p0.999:  23.876 ms/op
                 getUser·p0.9999: 26.837 ms/op
                 getUser·p1.00:   30.999 ms/op

Iteration   2: 4.022 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.999 ms/op
                 getUser·p0.50:   3.895 ms/op
                 getUser·p0.90:   4.661 ms/op
                 getUser·p0.95:   5.046 ms/op
                 getUser·p0.99:   6.872 ms/op
                 getUser·p0.999:  10.076 ms/op
                 getUser·p0.9999: 30.867 ms/op
                 getUser·p1.00:   31.556 ms/op

Iteration   3: 3.902 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.868 ms/op
                 getUser·p0.50:   3.715 ms/op
                 getUser·p0.90:   4.358 ms/op
                 getUser·p0.95:   4.678 ms/op
                 getUser·p0.99:   7.848 ms/op
                 getUser·p0.999:  26.642 ms/op
                 getUser·p0.9999: 35.364 ms/op
                 getUser·p1.00:   37.683 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 241580
  mean =      3.972 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 89 
    [ 2.500,  5.000) = 229869 
    [ 5.000,  7.500) = 8069 
    [ 7.500, 10.000) = 2860 
    [10.000, 12.500) = 366 
    [12.500, 15.000) = 39 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 56 
    [25.000, 27.500) = 113 
    [27.500, 30.000) = 36 
    [30.000, 32.500) = 24 
    [32.500, 35.000) = 21 
    [35.000, 37.500) = 10 

  Percentiles, ms/op:
      p(0.0000) =      1.188 ms/op
     p(50.0000) =      3.785 ms/op
     p(90.0000) =      4.489 ms/op
     p(95.0000) =      4.964 ms/op
     p(99.0000) =      7.995 ms/op
     p(99.9000) =     23.560 ms/op
     p(99.9900) =     34.003 ms/op
     p(99.9990) =     37.421 ms/op
     p(99.9999) =     37.683 ms/op
    p(100.0000) =     37.683 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 15.061 ±(99.9%) 0.215 ms/op
# Warmup Iteration   2: 5.475 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 4.896 ±(99.9%) 0.018 ms/op
Iteration   1: 4.760 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.667 ms/op
                 listUser·p0.50:   4.596 ms/op
                 listUser·p0.90:   5.235 ms/op
                 listUser·p0.95:   5.521 ms/op
                 listUser·p0.99:   8.421 ms/op
                 listUser·p0.999:  25.980 ms/op
                 listUser·p0.9999: 34.341 ms/op
                 listUser·p1.00:   35.127 ms/op

Iteration   2: 4.693 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.728 ms/op
                 listUser·p0.50:   4.522 ms/op
                 listUser·p0.90:   5.243 ms/op
                 listUser·p0.95:   5.612 ms/op
                 listUser·p0.99:   8.020 ms/op
                 listUser·p0.999:  16.122 ms/op
                 listUser·p0.9999: 22.327 ms/op
                 listUser·p1.00:   22.807 ms/op

Iteration   3: 4.621 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.224 ms/op
                 listUser·p0.50:   4.489 ms/op
                 listUser·p0.90:   5.054 ms/op
                 listUser·p0.95:   5.325 ms/op
                 listUser·p0.99:   8.027 ms/op
                 listUser·p0.999:  16.761 ms/op
                 listUser·p0.9999: 19.500 ms/op
                 listUser·p1.00:   20.742 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 204403
  mean =      4.691 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8 
    [ 2.500,  5.000) = 172040 
    [ 5.000,  7.500) = 29157 
    [ 7.500, 10.000) = 2400 
    [10.000, 12.500) = 340 
    [12.500, 15.000) = 56 
    [15.000, 17.500) = 174 
    [17.500, 20.000) = 40 
    [20.000, 22.500) = 54 
    [22.500, 25.000) = 53 
    [25.000, 27.500) = 17 
    [27.500, 30.000) = 14 
    [30.000, 32.500) = 34 
    [32.500, 35.000) = 15 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.667 ms/op
     p(50.0000) =      4.530 ms/op
     p(90.0000) =      5.177 ms/op
     p(95.0000) =      5.489 ms/op
     p(99.0000) =      8.225 ms/op
     p(99.9000) =     19.012 ms/op
     p(99.9900) =     32.237 ms/op
     p(99.9990) =     34.669 ms/op
     p(99.9999) =     35.127 ms/op
    p(100.0000) =     35.127 ms/op


# Run complete. Total time: 00:13:16

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.711 ± 7.218  ops/ms
ClientPb.existUser                       thrpt       3   8.524 ± 3.012  ops/ms
ClientPb.getUser                         thrpt       3   8.003 ± 5.466  ops/ms
ClientPb.listUser                        thrpt       3   6.865 ± 0.643  ops/ms
ClientPb.createUser                       avgt       3   3.936 ± 0.770   ms/op
ClientPb.existUser                        avgt       3   3.836 ± 1.153   ms/op
ClientPb.getUser                          avgt       3   3.990 ± 1.221   ms/op
ClientPb.listUser                         avgt       3   4.546 ± 1.814   ms/op
ClientPb.createUser                     sample  236074   4.066 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.851           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.908           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.710           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.259           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.234           ms/op
ClientPb.createUser:createUser·p0.999   sample          24.576           ms/op
ClientPb.createUser:createUser·p0.9999  sample          32.375           ms/op
ClientPb.createUser:createUser·p1.00    sample          34.603           ms/op
ClientPb.existUser                      sample  249351   3.848 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.931           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.690           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.334           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.760           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.578           ms/op
ClientPb.existUser:existUser·p0.999     sample          19.256           ms/op
ClientPb.existUser:existUser·p0.9999    sample          29.198           ms/op
ClientPb.existUser:existUser·p1.00      sample          31.687           ms/op
ClientPb.getUser                        sample  241580   3.972 ± 0.008   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.188           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.785           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.489           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.964           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.995           ms/op
ClientPb.getUser:getUser·p0.999         sample          23.560           ms/op
ClientPb.getUser:getUser·p0.9999        sample          34.003           ms/op
ClientPb.getUser:getUser·p1.00          sample          37.683           ms/op
ClientPb.listUser                       sample  204403   4.691 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.667           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.530           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.177           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.489           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.225           ms/op
ClientPb.listUser:listUser·p0.999       sample          19.012           ms/op
ClientPb.listUser:listUser·p0.9999      sample          32.237           ms/op
ClientPb.listUser:listUser·p1.00        sample          35.127           ms/op
