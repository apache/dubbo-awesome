# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.974 ops/ms
# Warmup Iteration   2: 11.962 ops/ms
# Warmup Iteration   3: 12.440 ops/ms
Iteration   1: 12.670 ops/ms
Iteration   2: 12.799 ops/ms
Iteration   3: 12.944 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.804 ±(99.9%) 2.506 ops/ms [Average]
  (min, avg, max) = (12.670, 12.804, 12.944), stdev = 0.137
  CI (99.9%): [10.298, 15.310] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.927 ops/ms
# Warmup Iteration   2: 13.256 ops/ms
# Warmup Iteration   3: 13.079 ops/ms
Iteration   1: 13.206 ops/ms
Iteration   2: 13.338 ops/ms
Iteration   3: 13.270 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.271 ±(99.9%) 1.202 ops/ms [Average]
  (min, avg, max) = (13.206, 13.271, 13.338), stdev = 0.066
  CI (99.9%): [12.069, 14.473] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:47
# Fork: 1 of 1
# Warmup Iteration   1: 8.177 ops/ms
# Warmup Iteration   2: 12.725 ops/ms
# Warmup Iteration   3: 12.782 ops/ms
Iteration   1: 12.817 ops/ms
Iteration   2: 12.805 ops/ms
Iteration   3: 12.633 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.752 ±(99.9%) 1.884 ops/ms [Average]
  (min, avg, max) = (12.633, 12.752, 12.817), stdev = 0.103
  CI (99.9%): [10.868, 14.635] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.680 ops/ms
# Warmup Iteration   2: 10.771 ops/ms
# Warmup Iteration   3: 10.922 ops/ms
Iteration   1: 11.001 ops/ms
Iteration   2: 10.964 ops/ms
Iteration   3: 10.796 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.920 ±(99.9%) 1.986 ops/ms [Average]
  (min, avg, max) = (10.796, 10.920, 11.001), stdev = 0.109
  CI (99.9%): [8.935, 12.906] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:37
# Fork: 1 of 1
# Warmup Iteration   1: 3.921 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.559 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.494 ±(99.9%) 0.003 ms/op
Iteration   1: 2.516 ±(99.9%) 0.005 ms/op
Iteration   2: 2.478 ±(99.9%) 0.004 ms/op
Iteration   3: 2.408 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.467 ±(99.9%) 0.992 ms/op [Average]
  (min, avg, max) = (2.408, 2.467, 2.516), stdev = 0.054
  CI (99.9%): [1.475, 3.459] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:32
# Fork: 1 of 1
# Warmup Iteration   1: 3.583 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.431 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.454 ±(99.9%) 0.003 ms/op
Iteration   1: 2.445 ±(99.9%) 0.003 ms/op
Iteration   2: 2.450 ±(99.9%) 0.004 ms/op
Iteration   3: 2.447 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.448 ±(99.9%) 0.048 ms/op [Average]
  (min, avg, max) = (2.445, 2.448, 2.450), stdev = 0.003
  CI (99.9%): [2.400, 2.496] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.668 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.494 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.460 ±(99.9%) 0.004 ms/op
Iteration   1: 2.469 ±(99.9%) 0.004 ms/op
Iteration   2: 2.487 ±(99.9%) 0.004 ms/op
Iteration   3: 2.470 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.475 ±(99.9%) 0.182 ms/op [Average]
  (min, avg, max) = (2.469, 2.475, 2.487), stdev = 0.010
  CI (99.9%): [2.293, 2.657] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:23
# Fork: 1 of 1
# Warmup Iteration   1: 4.607 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.973 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.946 ±(99.9%) 0.005 ms/op
Iteration   1: 2.963 ±(99.9%) 0.006 ms/op
Iteration   2: 2.972 ±(99.9%) 0.005 ms/op
Iteration   3: 2.992 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.976 ±(99.9%) 0.272 ms/op [Average]
  (min, avg, max) = (2.963, 2.976, 2.992), stdev = 0.015
  CI (99.9%): [2.704, 3.248] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:18
# Fork: 1 of 1
# Warmup Iteration   1: 4.276 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 2.619 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.558 ±(99.9%) 0.007 ms/op
Iteration   1: 2.526 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.124 ms/op
                 createUser·p0.50:   2.593 ms/op
                 createUser·p0.90:   3.064 ms/op
                 createUser·p0.95:   3.195 ms/op
                 createUser·p0.99:   3.891 ms/op
                 createUser·p0.999:  11.256 ms/op
                 createUser·p0.9999: 13.637 ms/op
                 createUser·p1.00:   14.254 ms/op

Iteration   2: 2.515 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.946 ms/op
                 createUser·p0.50:   2.605 ms/op
                 createUser·p0.90:   3.039 ms/op
                 createUser·p0.95:   3.142 ms/op
                 createUser·p0.99:   3.625 ms/op
                 createUser·p0.999:  9.470 ms/op
                 createUser·p0.9999: 12.591 ms/op
                 createUser·p1.00:   13.156 ms/op

Iteration   3: 2.526 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.007 ms/op
                 createUser·p0.50:   2.621 ms/op
                 createUser·p0.90:   3.064 ms/op
                 createUser·p0.95:   3.191 ms/op
                 createUser·p0.99:   4.059 ms/op
                 createUser·p0.999:  8.723 ms/op
                 createUser·p0.9999: 10.972 ms/op
                 createUser·p1.00:   14.172 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 380230
  mean =      2.522 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 32 
    [ 1.250,  2.500) = 182568 
    [ 2.500,  3.750) = 193096 
    [ 3.750,  5.000) = 3474 
    [ 5.000,  6.250) = 569 
    [ 6.250,  7.500) = 61 
    [ 7.500,  8.750) = 40 
    [ 8.750, 10.000) = 97 
    [10.000, 11.250) = 96 
    [11.250, 12.500) = 113 
    [12.500, 13.750) = 71 
    [13.750, 15.000) = 13 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.946 ms/op
     p(50.0000) =      2.609 ms/op
     p(90.0000) =      3.056 ms/op
     p(95.0000) =      3.174 ms/op
     p(99.0000) =      3.863 ms/op
     p(99.9000) =      8.815 ms/op
     p(99.9900) =     13.206 ms/op
     p(99.9990) =     14.192 ms/op
     p(99.9999) =     14.254 ms/op
    p(100.0000) =     14.254 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.863 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.503 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.466 ±(99.9%) 0.005 ms/op
Iteration   1: 2.450 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.983 ms/op
                 existUser·p0.50:   2.523 ms/op
                 existUser·p0.90:   2.966 ms/op
                 existUser·p0.95:   3.076 ms/op
                 existUser·p0.99:   3.596 ms/op
                 existUser·p0.999:  6.816 ms/op
                 existUser·p0.9999: 13.939 ms/op
                 existUser·p1.00:   14.828 ms/op

Iteration   2: 2.448 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.821 ms/op
                 existUser·p0.50:   2.474 ms/op
                 existUser·p0.90:   2.982 ms/op
                 existUser·p0.95:   3.080 ms/op
                 existUser·p0.99:   3.412 ms/op
                 existUser·p0.999:  8.576 ms/op
                 existUser·p0.9999: 12.908 ms/op
                 existUser·p1.00:   13.271 ms/op

Iteration   3: 2.458 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.884 ms/op
                 existUser·p0.50:   2.580 ms/op
                 existUser·p0.90:   2.974 ms/op
                 existUser·p0.95:   3.080 ms/op
                 existUser·p0.99:   3.703 ms/op
                 existUser·p0.999:  7.020 ms/op
                 existUser·p0.9999: 12.124 ms/op
                 existUser·p1.00:   12.993 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 391110
  mean =      2.452 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 58 
    [ 1.250,  2.500) = 193439 
    [ 2.500,  3.750) = 194746 
    [ 3.750,  5.000) = 2160 
    [ 5.000,  6.250) = 234 
    [ 6.250,  7.500) = 65 
    [ 7.500,  8.750) = 46 
    [ 8.750, 10.000) = 81 
    [10.000, 11.250) = 92 
    [11.250, 12.500) = 101 
    [12.500, 13.750) = 68 
    [13.750, 15.000) = 20 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.821 ms/op
     p(50.0000) =      2.523 ms/op
     p(90.0000) =      2.974 ms/op
     p(95.0000) =      3.076 ms/op
     p(99.0000) =      3.564 ms/op
     p(99.9000) =      8.518 ms/op
     p(99.9900) =     13.114 ms/op
     p(99.9990) =     14.503 ms/op
     p(99.9999) =     14.828 ms/op
    p(100.0000) =     14.828 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.830 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 2.512 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.498 ±(99.9%) 0.006 ms/op
Iteration   1: 2.477 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.733 ms/op
                 getUser·p0.50:   2.482 ms/op
                 getUser·p0.90:   3.015 ms/op
                 getUser·p0.95:   3.113 ms/op
                 getUser·p0.99:   3.527 ms/op
                 getUser·p0.999:  6.383 ms/op
                 getUser·p0.9999: 13.271 ms/op
                 getUser·p1.00:   13.910 ms/op

Iteration   2: 2.473 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.969 ms/op
                 getUser·p0.50:   2.499 ms/op
                 getUser·p0.90:   3.019 ms/op
                 getUser·p0.95:   3.150 ms/op
                 getUser·p0.99:   3.826 ms/op
                 getUser·p0.999:  8.542 ms/op
                 getUser·p0.9999: 12.845 ms/op
                 getUser·p1.00:   13.615 ms/op

Iteration   3: 2.476 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.069 ms/op
                 getUser·p0.50:   2.494 ms/op
                 getUser·p0.90:   3.023 ms/op
                 getUser·p0.95:   3.154 ms/op
                 getUser·p0.99:   3.817 ms/op
                 getUser·p0.999:  6.660 ms/op
                 getUser·p0.9999: 10.214 ms/op
                 getUser·p1.00:   10.846 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 387484
  mean =      2.475 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 75 
    [ 1.250,  2.500) = 194194 
    [ 2.500,  3.750) = 189467 
    [ 3.750,  5.000) = 2890 
    [ 5.000,  6.250) = 418 
    [ 6.250,  7.500) = 50 
    [ 7.500,  8.750) = 29 
    [ 8.750, 10.000) = 92 
    [10.000, 11.250) = 100 
    [11.250, 12.500) = 77 
    [12.500, 13.750) = 91 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.733 ms/op
     p(50.0000) =      2.494 ms/op
     p(90.0000) =      3.019 ms/op
     p(95.0000) =      3.138 ms/op
     p(99.0000) =      3.727 ms/op
     p(99.9000) =      7.852 ms/op
     p(99.9900) =     13.058 ms/op
     p(99.9990) =     13.586 ms/op
     p(99.9999) =     13.910 ms/op
    p(100.0000) =     13.910 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.605 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.019 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.997 ±(99.9%) 0.008 ms/op
Iteration   1: 2.979 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.816 ms/op
                 listUser·p0.50:   2.908 ms/op
                 listUser·p0.90:   3.863 ms/op
                 listUser·p0.95:   4.383 ms/op
                 listUser·p0.99:   5.554 ms/op
                 listUser·p0.999:  9.050 ms/op
                 listUser·p0.9999: 12.100 ms/op
                 listUser·p1.00:   13.173 ms/op

Iteration   2: 2.958 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.719 ms/op
                 listUser·p0.50:   2.892 ms/op
                 listUser·p0.90:   3.797 ms/op
                 listUser·p0.95:   4.309 ms/op
                 listUser·p0.99:   5.554 ms/op
                 listUser·p0.999:  9.516 ms/op
                 listUser·p0.9999: 12.340 ms/op
                 listUser·p1.00:   13.058 ms/op

Iteration   3: 2.951 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.825 ms/op
                 listUser·p0.50:   2.892 ms/op
                 listUser·p0.90:   3.809 ms/op
                 listUser·p0.95:   4.325 ms/op
                 listUser·p0.99:   5.448 ms/op
                 listUser·p0.999:  9.169 ms/op
                 listUser·p0.9999: 10.469 ms/op
                 listUser·p1.00:   11.502 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 323747
  mean =      2.963 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 171 
    [ 1.250,  2.500) = 100844 
    [ 2.500,  3.750) = 186559 
    [ 3.750,  5.000) = 29296 
    [ 5.000,  6.250) = 5667 
    [ 6.250,  7.500) = 528 
    [ 7.500,  8.750) = 232 
    [ 8.750, 10.000) = 276 
    [10.000, 11.250) = 93 
    [11.250, 12.500) = 65 
    [12.500, 13.750) = 16 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.719 ms/op
     p(50.0000) =      2.896 ms/op
     p(90.0000) =      3.822 ms/op
     p(95.0000) =      4.342 ms/op
     p(99.0000) =      5.530 ms/op
     p(99.9000) =      9.245 ms/op
     p(99.9900) =     12.167 ms/op
     p(99.9990) =     13.038 ms/op
     p(99.9999) =     13.173 ms/op
    p(100.0000) =     13.173 ms/op


# Run complete. Total time: 00:12:57

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.804 ± 2.506  ops/ms
ClientPb.existUser                       thrpt       3  13.271 ± 1.202  ops/ms
ClientPb.getUser                         thrpt       3  12.752 ± 1.884  ops/ms
ClientPb.listUser                        thrpt       3  10.920 ± 1.986  ops/ms
ClientPb.createUser                       avgt       3   2.467 ± 0.992   ms/op
ClientPb.existUser                        avgt       3   2.448 ± 0.048   ms/op
ClientPb.getUser                          avgt       3   2.475 ± 0.182   ms/op
ClientPb.listUser                         avgt       3   2.976 ± 0.272   ms/op
ClientPb.createUser                     sample  380230   2.522 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.946           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.609           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.056           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.174           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.863           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.815           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.206           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.254           ms/op
ClientPb.existUser                      sample  391110   2.452 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.821           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.523           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.974           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.076           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.564           ms/op
ClientPb.existUser:existUser·p0.999     sample           8.518           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.114           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.828           ms/op
ClientPb.getUser                        sample  387484   2.475 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.733           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.494           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.019           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.138           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.727           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.852           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.058           ms/op
ClientPb.getUser:getUser·p1.00          sample          13.910           ms/op
ClientPb.listUser                       sample  323747   2.963 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.719           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.896           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.822           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.342           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.530           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.245           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.167           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.173           ms/op
