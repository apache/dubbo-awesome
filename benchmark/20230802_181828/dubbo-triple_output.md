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
# Warmup Iteration   1: 2.164 ops/ms
# Warmup Iteration   2: 5.243 ops/ms
# Warmup Iteration   3: 8.379 ops/ms
Iteration   1: 8.654 ops/ms
Iteration   2: 8.771 ops/ms
Iteration   3: 9.226 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.884 ±(99.9%) 5.513 ops/ms [Average]
  (min, avg, max) = (8.654, 8.884, 9.226), stdev = 0.302
  CI (99.9%): [3.371, 14.396] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 2.620 ops/ms
# Warmup Iteration   2: 7.826 ops/ms
# Warmup Iteration   3: 9.059 ops/ms
Iteration   1: 9.063 ops/ms
Iteration   2: 9.023 ops/ms
Iteration   3: 9.129 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.072 ±(99.9%) 0.982 ops/ms [Average]
  (min, avg, max) = (9.023, 9.072, 9.129), stdev = 0.054
  CI (99.9%): [8.090, 10.054] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 2.434 ops/ms
# Warmup Iteration   2: 7.789 ops/ms
# Warmup Iteration   3: 8.819 ops/ms
Iteration   1: 8.991 ops/ms
Iteration   2: 9.196 ops/ms
Iteration   3: 9.093 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.093 ±(99.9%) 1.871 ops/ms [Average]
  (min, avg, max) = (8.991, 9.093, 9.196), stdev = 0.103
  CI (99.9%): [7.222, 10.964] (assumes normal distribution)


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
# Warmup Iteration   1: 2.421 ops/ms
# Warmup Iteration   2: 6.674 ops/ms
# Warmup Iteration   3: 7.531 ops/ms
Iteration   1: 7.820 ops/ms
Iteration   2: 7.764 ops/ms
Iteration   3: 7.453 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.679 ±(99.9%) 3.607 ops/ms [Average]
  (min, avg, max) = (7.453, 7.679, 7.820), stdev = 0.198
  CI (99.9%): [4.072, 11.286] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 10.432 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.991 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.798 ±(99.9%) 0.003 ms/op
Iteration   1: 3.557 ±(99.9%) 0.008 ms/op
Iteration   2: 3.645 ±(99.9%) 0.004 ms/op
Iteration   3: 3.563 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.588 ±(99.9%) 0.901 ms/op [Average]
  (min, avg, max) = (3.557, 3.588, 3.645), stdev = 0.049
  CI (99.9%): [2.687, 4.489] (assumes normal distribution)


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
# Warmup Iteration   1: 8.650 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.801 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.477 ±(99.9%) 0.004 ms/op
Iteration   1: 3.370 ±(99.9%) 0.009 ms/op
Iteration   2: 3.478 ±(99.9%) 0.004 ms/op
Iteration   3: 3.405 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.417 ±(99.9%) 1.010 ms/op [Average]
  (min, avg, max) = (3.370, 3.417, 3.478), stdev = 0.055
  CI (99.9%): [2.408, 4.427] (assumes normal distribution)


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
# Warmup Iteration   1: 10.377 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 4.018 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.704 ±(99.9%) 0.004 ms/op
Iteration   1: 3.596 ±(99.9%) 0.004 ms/op
Iteration   2: 3.670 ±(99.9%) 0.007 ms/op
Iteration   3: 3.603 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.623 ±(99.9%) 0.750 ms/op [Average]
  (min, avg, max) = (3.596, 3.623, 3.670), stdev = 0.041
  CI (99.9%): [2.873, 4.373] (assumes normal distribution)


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
# Warmup Iteration   1: 12.128 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 4.631 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 4.298 ±(99.9%) 0.006 ms/op
Iteration   1: 4.200 ±(99.9%) 0.007 ms/op
Iteration   2: 4.146 ±(99.9%) 0.008 ms/op
Iteration   3: 4.176 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.174 ±(99.9%) 0.494 ms/op [Average]
  (min, avg, max) = (4.146, 4.174, 4.200), stdev = 0.027
  CI (99.9%): [3.680, 4.667] (assumes normal distribution)


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
# Warmup Iteration   1: 11.048 ±(99.9%) 0.131 ms/op
# Warmup Iteration   2: 4.180 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 3.784 ±(99.9%) 0.014 ms/op
Iteration   1: 3.615 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.407 ms/op
                 createUser·p0.50:   3.457 ms/op
                 createUser·p0.90:   4.235 ms/op
                 createUser·p0.95:   4.645 ms/op
                 createUser·p0.99:   6.529 ms/op
                 createUser·p0.999:  23.495 ms/op
                 createUser·p0.9999: 30.540 ms/op
                 createUser·p1.00:   32.014 ms/op

Iteration   2: 3.684 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.421 ms/op
                 createUser·p0.50:   3.461 ms/op
                 createUser·p0.90:   4.317 ms/op
                 createUser·p0.95:   4.702 ms/op
                 createUser·p0.99:   6.840 ms/op
                 createUser·p0.999:  23.495 ms/op
                 createUser·p0.9999: 26.487 ms/op
                 createUser·p1.00:   27.754 ms/op

Iteration   3: 3.776 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.817 ms/op
                 createUser·p0.50:   3.596 ms/op
                 createUser·p0.90:   4.432 ms/op
                 createUser·p0.95:   4.784 ms/op
                 createUser·p0.99:   6.406 ms/op
                 createUser·p0.999:  15.347 ms/op
                 createUser·p0.9999: 28.119 ms/op
                 createUser·p1.00:   28.541 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 259862
  mean =      3.691 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4124 
    [ 2.500,  5.000) = 246043 
    [ 5.000,  7.500) = 8152 
    [ 7.500, 10.000) = 1021 
    [10.000, 12.500) = 204 
    [12.500, 15.000) = 9 
    [15.000, 17.500) = 49 
    [17.500, 20.000) = 4 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 114 
    [25.000, 27.500) = 94 
    [27.500, 30.000) = 35 
    [30.000, 32.500) = 13 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.407 ms/op
     p(50.0000) =      3.518 ms/op
     p(90.0000) =      4.350 ms/op
     p(95.0000) =      4.710 ms/op
     p(99.0000) =      6.545 ms/op
     p(99.9000) =     17.601 ms/op
     p(99.9900) =     28.935 ms/op
     p(99.9990) =     31.262 ms/op
     p(99.9999) =     32.014 ms/op
    p(100.0000) =     32.014 ms/op


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
# Warmup Iteration   1: 9.724 ±(99.9%) 0.124 ms/op
# Warmup Iteration   2: 3.722 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.588 ±(99.9%) 0.010 ms/op
Iteration   1: 3.536 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.944 ms/op
                 existUser·p0.50:   3.457 ms/op
                 existUser·p0.90:   3.891 ms/op
                 existUser·p0.95:   4.366 ms/op
                 existUser·p0.99:   6.496 ms/op
                 existUser·p0.999:  21.054 ms/op
                 existUser·p0.9999: 23.298 ms/op
                 existUser·p1.00:   24.576 ms/op

Iteration   2: 3.455 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.384 ms/op
                 existUser·p0.50:   3.371 ms/op
                 existUser·p0.90:   3.809 ms/op
                 existUser·p0.95:   4.088 ms/op
                 existUser·p0.99:   6.095 ms/op
                 existUser·p0.999:  10.535 ms/op
                 existUser·p0.9999: 26.706 ms/op
                 existUser·p1.00:   27.001 ms/op

Iteration   3: 3.585 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.720 ms/op
                 existUser·p0.50:   3.375 ms/op
                 existUser·p0.90:   4.051 ms/op
                 existUser·p0.95:   5.235 ms/op
                 existUser·p0.99:   7.291 ms/op
                 existUser·p0.999:  22.111 ms/op
                 existUser·p0.9999: 28.249 ms/op
                 existUser·p1.00:   29.917 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 272292
  mean =      3.524 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8719 
    [ 2.500,  5.000) = 254721 
    [ 5.000,  7.500) = 7042 
    [ 7.500, 10.000) = 1172 
    [10.000, 12.500) = 296 
    [12.500, 15.000) = 84 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 81 
    [22.500, 25.000) = 97 
    [25.000, 27.500) = 55 

  Percentiles, ms/op:
      p(0.0000) =      0.944 ms/op
     p(50.0000) =      3.412 ms/op
     p(90.0000) =      3.895 ms/op
     p(95.0000) =      4.415 ms/op
     p(99.0000) =      6.865 ms/op
     p(99.9000) =     14.139 ms/op
     p(99.9900) =     27.313 ms/op
     p(99.9990) =     29.340 ms/op
     p(99.9999) =     29.917 ms/op
    p(100.0000) =     29.917 ms/op


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
# Warmup Iteration   1: 9.028 ±(99.9%) 0.118 ms/op
# Warmup Iteration   2: 3.844 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.643 ±(99.9%) 0.013 ms/op
Iteration   1: 3.603 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.524 ms/op
                 getUser·p0.50:   3.469 ms/op
                 getUser·p0.90:   4.018 ms/op
                 getUser·p0.95:   4.514 ms/op
                 getUser·p0.99:   7.062 ms/op
                 getUser·p0.999:  23.265 ms/op
                 getUser·p0.9999: 29.134 ms/op
                 getUser·p1.00:   29.458 ms/op

Iteration   2: 3.564 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.266 ms/op
                 getUser·p0.50:   3.391 ms/op
                 getUser·p0.90:   4.088 ms/op
                 getUser·p0.95:   4.915 ms/op
                 getUser·p0.99:   6.709 ms/op
                 getUser·p0.999:  21.875 ms/op
                 getUser·p0.9999: 25.134 ms/op
                 getUser·p1.00:   25.788 ms/op

Iteration   3: 3.542 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   2.032 ms/op
                 getUser·p0.50:   3.441 ms/op
                 getUser·p0.90:   3.932 ms/op
                 getUser·p0.95:   4.309 ms/op
                 getUser·p0.99:   6.665 ms/op
                 getUser·p0.999:  11.989 ms/op
                 getUser·p0.9999: 37.944 ms/op
                 getUser·p1.00:   39.453 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 268831
  mean =      3.570 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5866 
    [ 2.500,  5.000) = 252589 
    [ 5.000,  7.500) = 8538 
    [ 7.500, 10.000) = 1341 
    [10.000, 12.500) = 130 
    [12.500, 15.000) = 65 
    [15.000, 17.500) = 44 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 109 
    [25.000, 27.500) = 52 
    [27.500, 30.000) = 43 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 17 

  Percentiles, ms/op:
      p(0.0000) =      1.266 ms/op
     p(50.0000) =      3.432 ms/op
     p(90.0000) =      4.014 ms/op
     p(95.0000) =      4.538 ms/op
     p(99.0000) =      6.813 ms/op
     p(99.9000) =     16.695 ms/op
     p(99.9900) =     36.577 ms/op
     p(99.9990) =     39.186 ms/op
     p(99.9999) =     39.453 ms/op
    p(100.0000) =     39.453 ms/op


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
# Warmup Iteration   1: 12.196 ±(99.9%) 0.167 ms/op
# Warmup Iteration   2: 4.777 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.402 ±(99.9%) 0.016 ms/op
Iteration   1: 4.103 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.821 ms/op
                 listUser·p0.50:   3.899 ms/op
                 listUser·p0.90:   4.628 ms/op
                 listUser·p0.95:   5.063 ms/op
                 listUser·p0.99:   8.208 ms/op
                 listUser·p0.999:  20.458 ms/op
                 listUser·p0.9999: 23.148 ms/op
                 listUser·p1.00:   23.953 ms/op

Iteration   2: 4.167 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.946 ms/op
                 listUser·p0.50:   3.973 ms/op
                 listUser·p0.90:   4.489 ms/op
                 listUser·p0.95:   4.833 ms/op
                 listUser·p0.99:   8.634 ms/op
                 listUser·p0.999:  19.431 ms/op
                 listUser·p0.9999: 23.527 ms/op
                 listUser·p1.00:   24.871 ms/op

Iteration   3: 4.209 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.866 ms/op
                 listUser·p0.50:   3.940 ms/op
                 listUser·p0.90:   4.694 ms/op
                 listUser·p0.95:   6.029 ms/op
                 listUser·p0.99:   9.503 ms/op
                 listUser·p0.999:  16.058 ms/op
                 listUser·p0.9999: 18.907 ms/op
                 listUser·p1.00:   18.907 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 230498
  mean =      4.159 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23 
    [ 2.500,  5.000) = 217289 
    [ 5.000,  7.500) = 8792 
    [ 7.500, 10.000) = 3023 
    [10.000, 12.500) = 759 
    [12.500, 15.000) = 149 
    [15.000, 17.500) = 173 
    [17.500, 20.000) = 149 
    [20.000, 22.500) = 108 
    [22.500, 25.000) = 33 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.821 ms/op
     p(50.0000) =      3.932 ms/op
     p(90.0000) =      4.588 ms/op
     p(95.0000) =      5.186 ms/op
     p(99.0000) =      8.716 ms/op
     p(99.9000) =     18.203 ms/op
     p(99.9900) =     23.000 ms/op
     p(99.9990) =     23.863 ms/op
     p(99.9999) =     24.871 ms/op
    p(100.0000) =     24.871 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.884 ± 5.513  ops/ms
ClientPb.existUser                       thrpt       3   9.072 ± 0.982  ops/ms
ClientPb.getUser                         thrpt       3   9.093 ± 1.871  ops/ms
ClientPb.listUser                        thrpt       3   7.679 ± 3.607  ops/ms
ClientPb.createUser                       avgt       3   3.588 ± 0.901   ms/op
ClientPb.existUser                        avgt       3   3.417 ± 1.010   ms/op
ClientPb.getUser                          avgt       3   3.623 ± 0.750   ms/op
ClientPb.listUser                         avgt       3   4.174 ± 0.494   ms/op
ClientPb.createUser                     sample  259862   3.691 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.407           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.518           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.350           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.710           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.545           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.601           ms/op
ClientPb.createUser:createUser·p0.9999  sample          28.935           ms/op
ClientPb.createUser:createUser·p1.00    sample          32.014           ms/op
ClientPb.existUser                      sample  272292   3.524 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.944           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.412           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.895           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.415           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.865           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.139           ms/op
ClientPb.existUser:existUser·p0.9999    sample          27.313           ms/op
ClientPb.existUser:existUser·p1.00      sample          29.917           ms/op
ClientPb.getUser                        sample  268831   3.570 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.266           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.432           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.014           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.538           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.813           ms/op
ClientPb.getUser:getUser·p0.999         sample          16.695           ms/op
ClientPb.getUser:getUser·p0.9999        sample          36.577           ms/op
ClientPb.getUser:getUser·p1.00          sample          39.453           ms/op
ClientPb.listUser                       sample  230498   4.159 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.821           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.932           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.588           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.186           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.716           ms/op
ClientPb.listUser:listUser·p0.999       sample          18.203           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.000           ms/op
ClientPb.listUser:listUser·p1.00        sample          24.871           ms/op
