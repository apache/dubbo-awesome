# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.095 ops/ms
# Warmup Iteration   2: 5.215 ops/ms
# Warmup Iteration   3: 8.163 ops/ms
Iteration   1: 9.092 ops/ms
Iteration   2: 9.461 ops/ms
Iteration   3: 8.799 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.117 ±(99.9%) 6.054 ops/ms [Average]
  (min, avg, max) = (8.799, 9.117, 9.461), stdev = 0.332
  CI (99.9%): [3.063, 15.171] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 3.255 ops/ms
# Warmup Iteration   2: 9.216 ops/ms
# Warmup Iteration   3: 8.975 ops/ms
Iteration   1: 9.553 ops/ms
Iteration   2: 9.992 ops/ms
Iteration   3: 9.988 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.844 ±(99.9%) 4.606 ops/ms [Average]
  (min, avg, max) = (9.553, 9.844, 9.992), stdev = 0.252
  CI (99.9%): [5.238, 14.451] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.142 ops/ms
# Warmup Iteration   2: 7.917 ops/ms
# Warmup Iteration   3: 9.305 ops/ms
Iteration   1: 9.327 ops/ms
Iteration   2: 9.440 ops/ms
Iteration   3: 9.163 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.310 ±(99.9%) 2.545 ops/ms [Average]
  (min, avg, max) = (9.163, 9.310, 9.440), stdev = 0.140
  CI (99.9%): [6.765, 11.855] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 2.943 ops/ms
# Warmup Iteration   2: 6.875 ops/ms
# Warmup Iteration   3: 7.603 ops/ms
Iteration   1: 7.876 ops/ms
Iteration   2: 7.941 ops/ms
Iteration   3: 7.864 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.893 ±(99.9%) 0.752 ops/ms [Average]
  (min, avg, max) = (7.864, 7.893, 7.941), stdev = 0.041
  CI (99.9%): [7.141, 8.646] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 10.794 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 4.098 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.625 ±(99.9%) 0.008 ms/op
Iteration   1: 3.433 ±(99.9%) 0.007 ms/op
Iteration   2: 3.452 ±(99.9%) 0.008 ms/op
Iteration   3: 3.405 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.430 ±(99.9%) 0.435 ms/op [Average]
  (min, avg, max) = (3.405, 3.430, 3.452), stdev = 0.024
  CI (99.9%): [2.995, 3.865] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 7.890 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.569 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.399 ±(99.9%) 0.010 ms/op
Iteration   1: 3.453 ±(99.9%) 0.005 ms/op
Iteration   2: 3.311 ±(99.9%) 0.006 ms/op
Iteration   3: 3.413 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.392 ±(99.9%) 1.331 ms/op [Average]
  (min, avg, max) = (3.311, 3.392, 3.453), stdev = 0.073
  CI (99.9%): [2.062, 4.723] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 9.046 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.768 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.761 ±(99.9%) 0.004 ms/op
Iteration   1: 3.544 ±(99.9%) 0.004 ms/op
Iteration   2: 3.436 ±(99.9%) 0.005 ms/op
Iteration   3: 3.488 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.489 ±(99.9%) 0.979 ms/op [Average]
  (min, avg, max) = (3.436, 3.489, 3.544), stdev = 0.054
  CI (99.9%): [2.510, 4.468] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 10.410 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 4.592 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.217 ±(99.9%) 0.007 ms/op
Iteration   1: 4.118 ±(99.9%) 0.008 ms/op
Iteration   2: 4.099 ±(99.9%) 0.007 ms/op
Iteration   3: 3.947 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.054 ±(99.9%) 1.712 ms/op [Average]
  (min, avg, max) = (3.947, 4.054, 4.118), stdev = 0.094
  CI (99.9%): [2.342, 5.767] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 10.081 ±(99.9%) 0.144 ms/op
# Warmup Iteration   2: 4.202 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.526 ±(99.9%) 0.010 ms/op
Iteration   1: 3.479 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.661 ms/op
                 createUser·p0.50:   3.346 ms/op
                 createUser·p0.90:   4.035 ms/op
                 createUser·p0.95:   4.506 ms/op
                 createUser·p0.99:   6.238 ms/op
                 createUser·p0.999:  19.595 ms/op
                 createUser·p0.9999: 24.281 ms/op
                 createUser·p1.00:   26.444 ms/op

Iteration   2: 3.375 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.599 ms/op
                 createUser·p0.50:   3.273 ms/op
                 createUser·p0.90:   3.764 ms/op
                 createUser·p0.95:   4.096 ms/op
                 createUser·p0.99:   5.587 ms/op
                 createUser·p0.999:  22.872 ms/op
                 createUser·p0.9999: 25.559 ms/op
                 createUser·p1.00:   25.821 ms/op

Iteration   3: 3.477 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.161 ms/op
                 createUser·p0.50:   3.310 ms/op
                 createUser·p0.90:   4.006 ms/op
                 createUser·p0.95:   4.342 ms/op
                 createUser·p0.99:   6.005 ms/op
                 createUser·p0.999:  17.992 ms/op
                 createUser·p0.9999: 25.612 ms/op
                 createUser·p1.00:   26.903 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 278786
  mean =      3.443 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10633 
    [ 2.500,  5.000) = 261163 
    [ 5.000,  7.500) = 6095 
    [ 7.500, 10.000) = 507 
    [10.000, 12.500) = 36 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 34 
    [17.500, 20.000) = 65 
    [20.000, 22.500) = 54 
    [22.500, 25.000) = 151 
    [25.000, 27.500) = 48 

  Percentiles, ms/op:
      p(0.0000) =      1.161 ms/op
     p(50.0000) =      3.310 ms/op
     p(90.0000) =      3.944 ms/op
     p(95.0000) =      4.309 ms/op
     p(99.0000) =      5.980 ms/op
     p(99.9000) =     19.019 ms/op
     p(99.9900) =     25.530 ms/op
     p(99.9990) =     26.479 ms/op
     p(99.9999) =     26.903 ms/op
    p(100.0000) =     26.903 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 9.025 ±(99.9%) 0.127 ms/op
# Warmup Iteration   2: 3.534 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.347 ±(99.9%) 0.009 ms/op
Iteration   1: 3.399 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.688 ms/op
                 existUser·p0.50:   3.289 ms/op
                 existUser·p0.90:   3.805 ms/op
                 existUser·p0.95:   4.141 ms/op
                 existUser·p0.99:   5.734 ms/op
                 existUser·p0.999:  19.626 ms/op
                 existUser·p0.9999: 21.876 ms/op
                 existUser·p1.00:   22.970 ms/op

Iteration   2: 3.359 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.051 ms/op
                 existUser·p0.50:   3.207 ms/op
                 existUser·p0.90:   3.781 ms/op
                 existUser·p0.95:   4.325 ms/op
                 existUser·p0.99:   6.046 ms/op
                 existUser·p0.999:  21.358 ms/op
                 existUser·p0.9999: 24.706 ms/op
                 existUser·p1.00:   25.395 ms/op

Iteration   3: 3.268 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.450 ms/op
                 existUser·p0.50:   3.133 ms/op
                 existUser·p0.90:   3.678 ms/op
                 existUser·p0.95:   3.953 ms/op
                 existUser·p0.99:   5.210 ms/op
                 existUser·p0.999:  9.800 ms/op
                 existUser·p0.9999: 24.805 ms/op
                 existUser·p1.00:   25.362 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 287177
  mean =      3.341 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4469 
    [ 2.500,  5.000) = 276702 
    [ 5.000,  7.500) = 5268 
    [ 7.500, 10.000) = 381 
    [10.000, 12.500) = 69 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 39 
    [20.000, 22.500) = 135 
    [22.500, 25.000) = 104 
    [25.000, 27.500) = 10 

  Percentiles, ms/op:
      p(0.0000) =      1.051 ms/op
     p(50.0000) =      3.195 ms/op
     p(90.0000) =      3.756 ms/op
     p(95.0000) =      4.129 ms/op
     p(99.0000) =      5.693 ms/op
     p(99.9000) =     17.877 ms/op
     p(99.9900) =     24.552 ms/op
     p(99.9990) =     25.367 ms/op
     p(99.9999) =     25.395 ms/op
    p(100.0000) =     25.395 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 9.007 ±(99.9%) 0.114 ms/op
# Warmup Iteration   2: 3.734 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.584 ±(99.9%) 0.012 ms/op
Iteration   1: 3.535 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.965 ms/op
                 getUser·p0.50:   3.322 ms/op
                 getUser·p0.90:   3.928 ms/op
                 getUser·p0.95:   5.554 ms/op
                 getUser·p0.99:   7.004 ms/op
                 getUser·p0.999:  19.577 ms/op
                 getUser·p0.9999: 22.573 ms/op
                 getUser·p1.00:   23.134 ms/op

Iteration   2: 3.467 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.092 ms/op
                 getUser·p0.50:   3.367 ms/op
                 getUser·p0.90:   3.957 ms/op
                 getUser·p0.95:   4.293 ms/op
                 getUser·p0.99:   6.021 ms/op
                 getUser·p0.999:  21.496 ms/op
                 getUser·p0.9999: 24.609 ms/op
                 getUser·p1.00:   25.592 ms/op

Iteration   3: 3.437 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.023 ms/op
                 getUser·p0.50:   3.265 ms/op
                 getUser·p0.90:   3.842 ms/op
                 getUser·p0.95:   4.067 ms/op
                 getUser·p0.99:   6.390 ms/op
                 getUser·p0.999:  18.687 ms/op
                 getUser·p0.9999: 31.293 ms/op
                 getUser·p1.00:   31.949 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 275996
  mean =      3.479 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7665 
    [ 2.500,  5.000) = 258839 
    [ 5.000,  7.500) = 8327 
    [ 7.500, 10.000) = 737 
    [10.000, 12.500) = 110 
    [12.500, 15.000) = 30 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 40 
    [20.000, 22.500) = 92 
    [22.500, 25.000) = 89 
    [25.000, 27.500) = 22 
    [27.500, 30.000) = 15 
    [30.000, 32.500) = 30 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.965 ms/op
     p(50.0000) =      3.330 ms/op
     p(90.0000) =      3.908 ms/op
     p(95.0000) =      4.325 ms/op
     p(99.0000) =      6.676 ms/op
     p(99.9000) =     19.530 ms/op
     p(99.9900) =     30.304 ms/op
     p(99.9990) =     31.577 ms/op
     p(99.9999) =     31.949 ms/op
    p(100.0000) =     31.949 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 11.125 ±(99.9%) 0.149 ms/op
# Warmup Iteration   2: 4.329 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.081 ±(99.9%) 0.013 ms/op
Iteration   1: 3.941 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.757 ms/op
                 listUser·p0.50:   3.871 ms/op
                 listUser·p0.90:   4.129 ms/op
                 listUser·p0.95:   4.366 ms/op
                 listUser·p0.99:   6.824 ms/op
                 listUser·p0.999:  17.826 ms/op
                 listUser·p0.9999: 23.949 ms/op
                 listUser·p1.00:   24.740 ms/op

Iteration   2: 3.972 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.363 ms/op
                 listUser·p0.50:   3.772 ms/op
                 listUser·p0.90:   4.415 ms/op
                 listUser·p0.95:   4.743 ms/op
                 listUser·p0.99:   7.651 ms/op
                 listUser·p0.999:  15.237 ms/op
                 listUser·p0.9999: 20.183 ms/op
                 listUser·p1.00:   20.218 ms/op

Iteration   3: 4.082 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.097 ms/op
                 listUser·p0.50:   3.990 ms/op
                 listUser·p0.90:   4.407 ms/op
                 listUser·p0.95:   4.686 ms/op
                 listUser·p0.99:   7.234 ms/op
                 listUser·p0.999:  14.085 ms/op
                 listUser·p0.9999: 15.267 ms/op
                 listUser·p1.00:   15.483 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 240069
  mean =      3.998 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 30 
    [ 2.500,  5.000) = 231963 
    [ 5.000,  7.500) = 6050 
    [ 7.500, 10.000) = 1101 
    [10.000, 12.500) = 335 
    [12.500, 15.000) = 362 
    [15.000, 17.500) = 114 
    [17.500, 20.000) = 62 
    [20.000, 22.500) = 35 
    [22.500, 25.000) = 17 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.757 ms/op
     p(50.0000) =      3.863 ms/op
     p(90.0000) =      4.342 ms/op
     p(95.0000) =      4.612 ms/op
     p(99.0000) =      7.258 ms/op
     p(99.9000) =     14.893 ms/op
     p(99.9900) =     21.921 ms/op
     p(99.9990) =     24.510 ms/op
     p(99.9999) =     24.740 ms/op
    p(100.0000) =     24.740 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.117 ± 6.054  ops/ms
ClientPb.existUser                       thrpt       3   9.844 ± 4.606  ops/ms
ClientPb.getUser                         thrpt       3   9.310 ± 2.545  ops/ms
ClientPb.listUser                        thrpt       3   7.893 ± 0.752  ops/ms
ClientPb.createUser                       avgt       3   3.430 ± 0.435   ms/op
ClientPb.existUser                        avgt       3   3.392 ± 1.331   ms/op
ClientPb.getUser                          avgt       3   3.489 ± 0.979   ms/op
ClientPb.listUser                         avgt       3   4.054 ± 1.712   ms/op
ClientPb.createUser                     sample  278786   3.443 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.161           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.310           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.944           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.309           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.980           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.019           ms/op
ClientPb.createUser:createUser·p0.9999  sample          25.530           ms/op
ClientPb.createUser:createUser·p1.00    sample          26.903           ms/op
ClientPb.existUser                      sample  287177   3.341 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.051           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.195           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.756           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.129           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.693           ms/op
ClientPb.existUser:existUser·p0.999     sample          17.877           ms/op
ClientPb.existUser:existUser·p0.9999    sample          24.552           ms/op
ClientPb.existUser:existUser·p1.00      sample          25.395           ms/op
ClientPb.getUser                        sample  275996   3.479 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.965           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.330           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.908           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.325           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.676           ms/op
ClientPb.getUser:getUser·p0.999         sample          19.530           ms/op
ClientPb.getUser:getUser·p0.9999        sample          30.304           ms/op
ClientPb.getUser:getUser·p1.00          sample          31.949           ms/op
ClientPb.listUser                       sample  240069   3.998 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.757           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.863           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.342           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.612           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.258           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.893           ms/op
ClientPb.listUser:listUser·p0.9999      sample          21.921           ms/op
ClientPb.listUser:listUser·p1.00        sample          24.740           ms/op
