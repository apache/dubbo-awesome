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
# Warmup Iteration   1: 1.041 ops/ms
# Warmup Iteration   2: 2.375 ops/ms
# Warmup Iteration   3: 5.168 ops/ms
Iteration   1: 5.400 ops/ms
Iteration   2: 5.689 ops/ms
Iteration   3: 5.614 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.568 ±(99.9%) 2.737 ops/ms [Average]
  (min, avg, max) = (5.400, 5.568, 5.689), stdev = 0.150
  CI (99.9%): [2.831, 8.305] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:05
# Fork: 1 of 1
# Warmup Iteration   1: 1.484 ops/ms
# Warmup Iteration   2: 4.384 ops/ms
# Warmup Iteration   3: 5.976 ops/ms
Iteration   1: 6.175 ops/ms
Iteration   2: 6.028 ops/ms
Iteration   3: 6.124 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.109 ±(99.9%) 1.366 ops/ms [Average]
  (min, avg, max) = (6.028, 6.109, 6.175), stdev = 0.075
  CI (99.9%): [4.743, 7.475] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:02
# Fork: 1 of 1
# Warmup Iteration   1: 1.514 ops/ms
# Warmup Iteration   2: 4.149 ops/ms
# Warmup Iteration   3: 5.451 ops/ms
Iteration   1: 5.718 ops/ms
Iteration   2: 5.789 ops/ms
Iteration   3: 5.812 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.773 ±(99.9%) 0.895 ops/ms [Average]
  (min, avg, max) = (5.718, 5.773, 5.812), stdev = 0.049
  CI (99.9%): [4.878, 6.668] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:57
# Fork: 1 of 1
# Warmup Iteration   1: 1.460 ops/ms
# Warmup Iteration   2: 3.954 ops/ms
# Warmup Iteration   3: 4.893 ops/ms
Iteration   1: 5.005 ops/ms
Iteration   2: 5.125 ops/ms
Iteration   3: 5.144 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.091 ±(99.9%) 1.376 ops/ms [Average]
  (min, avg, max) = (5.005, 5.091, 5.144), stdev = 0.075
  CI (99.9%): [3.715, 6.467] (assumes normal distribution)


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
# Warmup Iteration   1: 18.505 ±(99.9%) 0.076 ms/op
# Warmup Iteration   2: 7.030 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 5.729 ±(99.9%) 0.017 ms/op
Iteration   1: 5.496 ±(99.9%) 0.013 ms/op
Iteration   2: 5.479 ±(99.9%) 0.012 ms/op
Iteration   3: 5.412 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.462 ±(99.9%) 0.812 ms/op [Average]
  (min, avg, max) = (5.412, 5.462, 5.496), stdev = 0.045
  CI (99.9%): [4.650, 6.274] (assumes normal distribution)


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
# Warmup Iteration   1: 17.996 ±(99.9%) 0.093 ms/op
# Warmup Iteration   2: 6.057 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 5.414 ±(99.9%) 0.009 ms/op
Iteration   1: 5.318 ±(99.9%) 0.013 ms/op
Iteration   2: 5.432 ±(99.9%) 0.010 ms/op
Iteration   3: 5.321 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.357 ±(99.9%) 1.184 ms/op [Average]
  (min, avg, max) = (5.318, 5.357, 5.432), stdev = 0.065
  CI (99.9%): [4.172, 6.541] (assumes normal distribution)


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
# Warmup Iteration   1: 17.274 ±(99.9%) 0.079 ms/op
# Warmup Iteration   2: 6.627 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 5.480 ±(99.9%) 0.008 ms/op
Iteration   1: 5.633 ±(99.9%) 0.008 ms/op
Iteration   2: 5.512 ±(99.9%) 0.011 ms/op
Iteration   3: 5.446 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.531 ±(99.9%) 1.729 ms/op [Average]
  (min, avg, max) = (5.446, 5.531, 5.633), stdev = 0.095
  CI (99.9%): [3.802, 7.259] (assumes normal distribution)


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
# Warmup Iteration   1: 19.492 ±(99.9%) 0.096 ms/op
# Warmup Iteration   2: 8.235 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 6.438 ±(99.9%) 0.014 ms/op
Iteration   1: 6.236 ±(99.9%) 0.011 ms/op
Iteration   2: 6.260 ±(99.9%) 0.010 ms/op
Iteration   3: 6.195 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.230 ±(99.9%) 0.598 ms/op [Average]
  (min, avg, max) = (6.195, 6.230, 6.260), stdev = 0.033
  CI (99.9%): [5.632, 6.828] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 17.546 ±(99.9%) 0.274 ms/op
# Warmup Iteration   2: 6.884 ±(99.9%) 0.040 ms/op
# Warmup Iteration   3: 6.141 ±(99.9%) 0.031 ms/op
Iteration   1: 5.396 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   2.601 ms/op
                 createUser·p0.50:   5.071 ms/op
                 createUser·p0.90:   6.685 ms/op
                 createUser·p0.95:   7.479 ms/op
                 createUser·p0.99:   10.265 ms/op
                 createUser·p0.999:  21.840 ms/op
                 createUser·p0.9999: 33.035 ms/op
                 createUser·p1.00:   33.686 ms/op

Iteration   2: 5.564 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   2.224 ms/op
                 createUser·p0.50:   5.259 ms/op
                 createUser·p0.90:   6.912 ms/op
                 createUser·p0.95:   7.856 ms/op
                 createUser·p0.99:   10.331 ms/op
                 createUser·p0.999:  15.585 ms/op
                 createUser·p0.9999: 30.630 ms/op
                 createUser·p1.00:   32.211 ms/op

Iteration   3: 5.653 ±(99.9%) 0.023 ms/op
                 createUser·p0.00:   1.997 ms/op
                 createUser·p0.50:   5.259 ms/op
                 createUser·p0.90:   7.152 ms/op
                 createUser·p0.95:   8.274 ms/op
                 createUser·p0.99:   11.534 ms/op
                 createUser·p0.999:  27.317 ms/op
                 createUser·p0.9999: 30.913 ms/op
                 createUser·p1.00:   31.883 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 173245
  mean =      5.535 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15 
    [ 2.500,  5.000) = 69759 
    [ 5.000,  7.500) = 92433 
    [ 7.500, 10.000) = 8553 
    [10.000, 12.500) = 1699 
    [12.500, 15.000) = 464 
    [15.000, 17.500) = 68 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 56 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 30 
    [27.500, 30.000) = 60 
    [30.000, 32.500) = 44 
    [32.500, 35.000) = 11 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.997 ms/op
     p(50.0000) =      5.177 ms/op
     p(90.0000) =      6.914 ms/op
     p(95.0000) =      7.856 ms/op
     p(99.0000) =     10.715 ms/op
     p(99.9000) =     22.422 ms/op
     p(99.9900) =     31.570 ms/op
     p(99.9990) =     33.638 ms/op
     p(99.9999) =     33.686 ms/op
    p(100.0000) =     33.686 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 18.696 ±(99.9%) 0.278 ms/op
# Warmup Iteration   2: 6.362 ±(99.9%) 0.039 ms/op
# Warmup Iteration   3: 5.457 ±(99.9%) 0.024 ms/op
Iteration   1: 5.396 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   2.032 ms/op
                 existUser·p0.50:   5.005 ms/op
                 existUser·p0.90:   6.881 ms/op
                 existUser·p0.95:   8.266 ms/op
                 existUser·p0.99:   10.699 ms/op
                 existUser·p0.999:  23.502 ms/op
                 existUser·p0.9999: 29.000 ms/op
                 existUser·p1.00:   30.802 ms/op

Iteration   2: 5.369 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   2.384 ms/op
                 existUser·p0.50:   5.046 ms/op
                 existUser·p0.90:   6.693 ms/op
                 existUser·p0.95:   8.077 ms/op
                 existUser·p0.99:   10.945 ms/op
                 existUser·p0.999:  14.652 ms/op
                 existUser·p0.9999: 28.606 ms/op
                 existUser·p1.00:   29.983 ms/op

Iteration   3: 5.225 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   2.540 ms/op
                 existUser·p0.50:   4.915 ms/op
                 existUser·p0.90:   6.382 ms/op
                 existUser·p0.95:   7.479 ms/op
                 existUser·p0.99:   10.915 ms/op
                 existUser·p0.999:  25.023 ms/op
                 existUser·p0.9999: 29.651 ms/op
                 existUser·p1.00:   30.310 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 180009
  mean =      5.329 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16 
    [ 2.500,  5.000) = 91610 
    [ 5.000,  7.500) = 76986 
    [ 7.500, 10.000) = 8593 
    [10.000, 12.500) = 2011 
    [12.500, 15.000) = 541 
    [15.000, 17.500) = 43 
    [17.500, 20.000) = 17 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 39 
    [25.000, 27.500) = 73 
    [27.500, 30.000) = 56 
    [30.000, 32.500) = 3 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.032 ms/op
     p(50.0000) =      4.989 ms/op
     p(90.0000) =      6.652 ms/op
     p(95.0000) =      8.020 ms/op
     p(99.0000) =     10.846 ms/op
     p(99.9000) =     22.053 ms/op
     p(99.9900) =     29.131 ms/op
     p(99.9990) =     30.409 ms/op
     p(99.9999) =     30.802 ms/op
    p(100.0000) =     30.802 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:13
# Fork: 1 of 1
# Warmup Iteration   1: 18.518 ±(99.9%) 0.282 ms/op
# Warmup Iteration   2: 6.543 ±(99.9%) 0.038 ms/op
# Warmup Iteration   3: 5.510 ±(99.9%) 0.021 ms/op
Iteration   1: 5.619 ±(99.9%) 0.023 ms/op
                 getUser·p0.00:   2.466 ms/op
                 getUser·p0.50:   5.226 ms/op
                 getUser·p0.90:   6.889 ms/op
                 getUser·p0.95:   8.241 ms/op
                 getUser·p0.99:   13.074 ms/op
                 getUser·p0.999:  22.970 ms/op
                 getUser·p0.9999: 27.099 ms/op
                 getUser·p1.00:   27.591 ms/op

Iteration   2: 5.465 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   1.606 ms/op
                 getUser·p0.50:   5.145 ms/op
                 getUser·p0.90:   6.775 ms/op
                 getUser·p0.95:   7.725 ms/op
                 getUser·p0.99:   10.142 ms/op
                 getUser·p0.999:  24.740 ms/op
                 getUser·p0.9999: 29.632 ms/op
                 getUser·p1.00:   30.573 ms/op

Iteration   3: 5.554 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   2.486 ms/op
                 getUser·p0.50:   5.226 ms/op
                 getUser·p0.90:   6.889 ms/op
                 getUser·p0.95:   8.004 ms/op
                 getUser·p0.99:   10.781 ms/op
                 getUser·p0.999:  27.001 ms/op
                 getUser·p0.9999: 30.195 ms/op
                 getUser·p1.00:   32.178 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 173000
  mean =      5.545 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4 
    [ 2.500,  5.000) = 67620 
    [ 5.000,  7.500) = 94016 
    [ 7.500, 10.000) = 8658 
    [10.000, 12.500) = 1607 
    [12.500, 15.000) = 512 
    [15.000, 17.500) = 240 
    [17.500, 20.000) = 64 
    [20.000, 22.500) = 59 
    [22.500, 25.000) = 57 
    [25.000, 27.500) = 91 
    [27.500, 30.000) = 61 
    [30.000, 32.500) = 11 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.606 ms/op
     p(50.0000) =      5.202 ms/op
     p(90.0000) =      6.849 ms/op
     p(95.0000) =      7.987 ms/op
     p(99.0000) =     11.158 ms/op
     p(99.9000) =     24.609 ms/op
     p(99.9900) =     29.668 ms/op
     p(99.9990) =     31.006 ms/op
     p(99.9999) =     32.178 ms/op
    p(100.0000) =     32.178 ms/op


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
# Warmup Iteration   1: 21.375 ±(99.9%) 0.351 ms/op
# Warmup Iteration   2: 8.409 ±(99.9%) 0.065 ms/op
# Warmup Iteration   3: 6.320 ±(99.9%) 0.025 ms/op
Iteration   1: 6.401 ±(99.9%) 0.028 ms/op
                 listUser·p0.00:   3.019 ms/op
                 listUser·p0.50:   5.997 ms/op
                 listUser·p0.90:   7.905 ms/op
                 listUser·p0.95:   9.191 ms/op
                 listUser·p0.99:   12.714 ms/op
                 listUser·p0.999:  31.612 ms/op
                 listUser·p0.9999: 35.258 ms/op
                 listUser·p1.00:   36.372 ms/op

Iteration   2: 6.610 ±(99.9%) 0.029 ms/op
                 listUser·p0.00:   2.527 ms/op
                 listUser·p0.50:   6.128 ms/op
                 listUser·p0.90:   8.503 ms/op
                 listUser·p0.95:   9.830 ms/op
                 listUser·p0.99:   13.681 ms/op
                 listUser·p0.999:  27.754 ms/op
                 listUser·p0.9999: 34.220 ms/op
                 listUser·p1.00:   34.931 ms/op

Iteration   3: 6.494 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   2.290 ms/op
                 listUser·p0.50:   5.980 ms/op
                 listUser·p0.90:   8.356 ms/op
                 listUser·p0.95:   9.732 ms/op
                 listUser·p0.99:   13.730 ms/op
                 listUser·p0.999:  25.693 ms/op
                 listUser·p0.9999: 30.968 ms/op
                 listUser·p1.00:   32.211 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 147697
  mean =      6.500 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1 
    [ 2.500,  5.000) = 7134 
    [ 5.000,  7.500) = 117525 
    [ 7.500, 10.000) = 17218 
    [10.000, 12.500) = 3739 
    [12.500, 15.000) = 1209 
    [15.000, 17.500) = 350 
    [17.500, 20.000) = 145 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 83 
    [25.000, 27.500) = 107 
    [27.500, 30.000) = 54 
    [30.000, 32.500) = 53 
    [32.500, 35.000) = 42 
    [35.000, 37.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      2.290 ms/op
     p(50.0000) =      6.029 ms/op
     p(90.0000) =      8.274 ms/op
     p(95.0000) =      9.552 ms/op
     p(99.0000) =     13.337 ms/op
     p(99.9000) =     27.699 ms/op
     p(99.9900) =     34.517 ms/op
     p(99.9990) =     36.216 ms/op
     p(99.9999) =     36.372 ms/op
    p(100.0000) =     36.372 ms/op


# Run complete. Total time: 00:13:18

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.568 ± 2.737  ops/ms
ClientPb.existUser                       thrpt       3   6.109 ± 1.366  ops/ms
ClientPb.getUser                         thrpt       3   5.773 ± 0.895  ops/ms
ClientPb.listUser                        thrpt       3   5.091 ± 1.376  ops/ms
ClientPb.createUser                       avgt       3   5.462 ± 0.812   ms/op
ClientPb.existUser                        avgt       3   5.357 ± 1.184   ms/op
ClientPb.getUser                          avgt       3   5.531 ± 1.729   ms/op
ClientPb.listUser                         avgt       3   6.230 ± 0.598   ms/op
ClientPb.createUser                     sample  173245   5.535 ± 0.012   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.997           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.177           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.914           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.856           ms/op
ClientPb.createUser:createUser·p0.99    sample          10.715           ms/op
ClientPb.createUser:createUser·p0.999   sample          22.422           ms/op
ClientPb.createUser:createUser·p0.9999  sample          31.570           ms/op
ClientPb.createUser:createUser·p1.00    sample          33.686           ms/op
ClientPb.existUser                      sample  180009   5.329 ± 0.011   ms/op
ClientPb.existUser:existUser·p0.00      sample           2.032           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.989           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.652           ms/op
ClientPb.existUser:existUser·p0.95      sample           8.020           ms/op
ClientPb.existUser:existUser·p0.99      sample          10.846           ms/op
ClientPb.existUser:existUser·p0.999     sample          22.053           ms/op
ClientPb.existUser:existUser·p0.9999    sample          29.131           ms/op
ClientPb.existUser:existUser·p1.00      sample          30.802           ms/op
ClientPb.getUser                        sample  173000   5.545 ± 0.012   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.606           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.202           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.849           ms/op
ClientPb.getUser:getUser·p0.95          sample           7.987           ms/op
ClientPb.getUser:getUser·p0.99          sample          11.158           ms/op
ClientPb.getUser:getUser·p0.999         sample          24.609           ms/op
ClientPb.getUser:getUser·p0.9999        sample          29.668           ms/op
ClientPb.getUser:getUser·p1.00          sample          32.178           ms/op
ClientPb.listUser                       sample  147697   6.500 ± 0.016   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.290           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.029           ms/op
ClientPb.listUser:listUser·p0.90        sample           8.274           ms/op
ClientPb.listUser:listUser·p0.95        sample           9.552           ms/op
ClientPb.listUser:listUser·p0.99        sample          13.337           ms/op
ClientPb.listUser:listUser·p0.999       sample          27.699           ms/op
ClientPb.listUser:listUser·p0.9999      sample          34.517           ms/op
ClientPb.listUser:listUser·p1.00        sample          36.372           ms/op
