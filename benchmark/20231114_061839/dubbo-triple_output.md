# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.684 ops/ms
# Warmup Iteration   2: 12.332 ops/ms
# Warmup Iteration   3: 12.389 ops/ms
Iteration   1: 12.833 ops/ms
Iteration   2: 12.867 ops/ms
Iteration   3: 12.898 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.866 ±(99.9%) 0.594 ops/ms [Average]
  (min, avg, max) = (12.833, 12.866, 12.898), stdev = 0.033
  CI (99.9%): [12.272, 13.460] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:53
# Fork: 1 of 1
# Warmup Iteration   1: 7.944 ops/ms
# Warmup Iteration   2: 12.881 ops/ms
# Warmup Iteration   3: 12.914 ops/ms
Iteration   1: 12.967 ops/ms
Iteration   2: 12.997 ops/ms
Iteration   3: 13.084 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.016 ±(99.9%) 1.112 ops/ms [Average]
  (min, avg, max) = (12.967, 13.016, 13.084), stdev = 0.061
  CI (99.9%): [11.904, 14.128] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:47
# Fork: 1 of 1
# Warmup Iteration   1: 7.964 ops/ms
# Warmup Iteration   2: 12.546 ops/ms
# Warmup Iteration   3: 12.670 ops/ms
Iteration   1: 12.751 ops/ms
Iteration   2: 12.698 ops/ms
Iteration   3: 12.802 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.750 ±(99.9%) 0.940 ops/ms [Average]
  (min, avg, max) = (12.698, 12.750, 12.802), stdev = 0.052
  CI (99.9%): [11.810, 13.690] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:43
# Fork: 1 of 1
# Warmup Iteration   1: 6.628 ops/ms
# Warmup Iteration   2: 10.518 ops/ms
# Warmup Iteration   3: 10.655 ops/ms
Iteration   1: 10.537 ops/ms
Iteration   2: 10.648 ops/ms
Iteration   3: 10.848 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.678 ±(99.9%) 2.872 ops/ms [Average]
  (min, avg, max) = (10.537, 10.678, 10.848), stdev = 0.157
  CI (99.9%): [7.805, 13.550] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:38
# Fork: 1 of 1
# Warmup Iteration   1: 3.881 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.509 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.438 ±(99.9%) 0.004 ms/op
Iteration   1: 2.490 ±(99.9%) 0.004 ms/op
Iteration   2: 2.485 ±(99.9%) 0.005 ms/op
Iteration   3: 2.448 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.474 ±(99.9%) 0.411 ms/op [Average]
  (min, avg, max) = (2.448, 2.474, 2.490), stdev = 0.023
  CI (99.9%): [2.063, 2.885] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:33
# Fork: 1 of 1
# Warmup Iteration   1: 3.799 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.485 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.438 ±(99.9%) 0.003 ms/op
Iteration   1: 2.425 ±(99.9%) 0.003 ms/op
Iteration   2: 2.425 ±(99.9%) 0.004 ms/op
Iteration   3: 2.439 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.430 ±(99.9%) 0.148 ms/op [Average]
  (min, avg, max) = (2.425, 2.430, 2.439), stdev = 0.008
  CI (99.9%): [2.282, 2.578] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:29
# Fork: 1 of 1
# Warmup Iteration   1: 3.963 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.542 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.505 ±(99.9%) 0.005 ms/op
Iteration   1: 2.487 ±(99.9%) 0.004 ms/op
Iteration   2: 2.462 ±(99.9%) 0.005 ms/op
Iteration   3: 2.513 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.487 ±(99.9%) 0.468 ms/op [Average]
  (min, avg, max) = (2.462, 2.487, 2.513), stdev = 0.026
  CI (99.9%): [2.019, 2.955] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 4.730 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.034 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.010 ±(99.9%) 0.004 ms/op
Iteration   1: 3.016 ±(99.9%) 0.005 ms/op
Iteration   2: 3.031 ±(99.9%) 0.006 ms/op
Iteration   3: 3.040 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.029 ±(99.9%) 0.218 ms/op [Average]
  (min, avg, max) = (3.016, 3.029, 3.040), stdev = 0.012
  CI (99.9%): [2.811, 3.247] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.107 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.643 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.500 ±(99.9%) 0.006 ms/op
Iteration   1: 2.478 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.936 ms/op
                 createUser·p0.50:   2.511 ms/op
                 createUser·p0.90:   3.006 ms/op
                 createUser·p0.95:   3.121 ms/op
                 createUser·p0.99:   3.789 ms/op
                 createUser·p0.999:  6.594 ms/op
                 createUser·p0.9999: 13.846 ms/op
                 createUser·p1.00:   14.057 ms/op

Iteration   2: 2.508 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.818 ms/op
                 createUser·p0.50:   2.572 ms/op
                 createUser·p0.90:   3.039 ms/op
                 createUser·p0.95:   3.178 ms/op
                 createUser·p0.99:   4.227 ms/op
                 createUser·p0.999:  9.372 ms/op
                 createUser·p0.9999: 14.078 ms/op
                 createUser·p1.00:   14.975 ms/op

Iteration   3: 2.512 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.856 ms/op
                 createUser·p0.50:   2.564 ms/op
                 createUser·p0.90:   3.060 ms/op
                 createUser·p0.95:   3.199 ms/op
                 createUser·p0.99:   4.063 ms/op
                 createUser·p0.999:  7.954 ms/op
                 createUser·p0.9999: 9.752 ms/op
                 createUser·p1.00:   10.109 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 383757
  mean =      2.499 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 67 
    [ 1.250,  2.500) = 187707 
    [ 2.500,  3.750) = 190654 
    [ 3.750,  5.000) = 3971 
    [ 5.000,  6.250) = 896 
    [ 6.250,  7.500) = 65 
    [ 7.500,  8.750) = 44 
    [ 8.750, 10.000) = 104 
    [10.000, 11.250) = 68 
    [11.250, 12.500) = 71 
    [12.500, 13.750) = 67 
    [13.750, 15.000) = 43 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.818 ms/op
     p(50.0000) =      2.548 ms/op
     p(90.0000) =      3.035 ms/op
     p(95.0000) =      3.166 ms/op
     p(99.0000) =      4.018 ms/op
     p(99.9000) =      7.958 ms/op
     p(99.9900) =     13.828 ms/op
     p(99.9990) =     14.743 ms/op
     p(99.9999) =     14.975 ms/op
    p(100.0000) =     14.975 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.966 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.440 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.443 ±(99.9%) 0.005 ms/op
Iteration   1: 2.441 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.017 ms/op
                 existUser·p0.50:   2.458 ms/op
                 existUser·p0.90:   2.978 ms/op
                 existUser·p0.95:   3.097 ms/op
                 existUser·p0.99:   3.822 ms/op
                 existUser·p0.999:  6.873 ms/op
                 existUser·p0.9999: 13.794 ms/op
                 existUser·p1.00:   14.762 ms/op

Iteration   2: 2.437 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.710 ms/op
                 existUser·p0.50:   2.523 ms/op
                 existUser·p0.90:   2.945 ms/op
                 existUser·p0.95:   3.039 ms/op
                 existUser·p0.99:   3.629 ms/op
                 existUser·p0.999:  7.803 ms/op
                 existUser·p0.9999: 16.974 ms/op
                 existUser·p1.00:   18.711 ms/op

Iteration   3: 2.436 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.937 ms/op
                 existUser·p0.50:   2.499 ms/op
                 existUser·p0.90:   2.957 ms/op
                 existUser·p0.95:   3.068 ms/op
                 existUser·p0.99:   3.711 ms/op
                 existUser·p0.999:  7.691 ms/op
                 existUser·p0.9999: 9.845 ms/op
                 existUser·p1.00:   10.453 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 393392
  mean =      2.438 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 46 
    [ 1.250,  2.500) = 197508 
    [ 2.500,  3.750) = 192022 
    [ 3.750,  5.000) = 2777 
    [ 5.000,  6.250) = 552 
    [ 6.250,  7.500) = 93 
    [ 7.500,  8.750) = 68 
    [ 8.750, 10.000) = 80 
    [10.000, 11.250) = 23 
    [11.250, 12.500) = 51 
    [12.500, 13.750) = 126 
    [13.750, 15.000) = 14 
    [15.000, 16.250) = 3 
    [16.250, 17.500) = 22 
    [17.500, 18.750) = 7 

  Percentiles, ms/op:
      p(0.0000) =      0.710 ms/op
     p(50.0000) =      2.490 ms/op
     p(90.0000) =      2.957 ms/op
     p(95.0000) =      3.068 ms/op
     p(99.0000) =      3.723 ms/op
     p(99.9000) =      7.524 ms/op
     p(99.9900) =     14.292 ms/op
     p(99.9990) =     18.424 ms/op
     p(99.9999) =     18.711 ms/op
    p(100.0000) =     18.711 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 3.910 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.570 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.465 ±(99.9%) 0.005 ms/op
Iteration   1: 2.496 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.774 ms/op
                 getUser·p0.50:   2.503 ms/op
                 getUser·p0.90:   3.039 ms/op
                 getUser·p0.95:   3.183 ms/op
                 getUser·p0.99:   4.174 ms/op
                 getUser·p0.999:  11.392 ms/op
                 getUser·p0.9999: 14.375 ms/op
                 getUser·p1.00:   15.679 ms/op

Iteration   2: 2.451 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.012 ms/op
                 getUser·p0.50:   2.499 ms/op
                 getUser·p0.90:   2.966 ms/op
                 getUser·p0.95:   3.052 ms/op
                 getUser·p0.99:   3.572 ms/op
                 getUser·p0.999:  6.750 ms/op
                 getUser·p0.9999: 14.857 ms/op
                 getUser·p1.00:   15.188 ms/op

Iteration   3: 2.500 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.874 ms/op
                 getUser·p0.50:   2.548 ms/op
                 getUser·p0.90:   3.006 ms/op
                 getUser·p0.95:   3.138 ms/op
                 getUser·p0.99:   4.489 ms/op
                 getUser·p0.999:  8.348 ms/op
                 getUser·p0.9999: 10.499 ms/op
                 getUser·p1.00:   11.993 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 386464
  mean =      2.482 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 51 
    [ 1.250,  2.500) = 191998 
    [ 2.500,  3.750) = 188625 
    [ 3.750,  5.000) = 4310 
    [ 5.000,  6.250) = 856 
    [ 6.250,  7.500) = 133 
    [ 7.500,  8.750) = 116 
    [ 8.750, 10.000) = 131 
    [10.000, 11.250) = 50 
    [11.250, 12.500) = 49 
    [12.500, 13.750) = 75 
    [13.750, 15.000) = 61 
    [15.000, 16.250) = 9 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.774 ms/op
     p(50.0000) =      2.519 ms/op
     p(90.0000) =      3.002 ms/op
     p(95.0000) =      3.121 ms/op
     p(99.0000) =      4.162 ms/op
     p(99.9000) =      8.327 ms/op
     p(99.9900) =     14.303 ms/op
     p(99.9990) =     15.192 ms/op
     p(99.9999) =     15.679 ms/op
    p(100.0000) =     15.679 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.748 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.035 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.989 ±(99.9%) 0.009 ms/op
Iteration   1: 2.999 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.905 ms/op
                 listUser·p0.50:   2.933 ms/op
                 listUser·p0.90:   3.891 ms/op
                 listUser·p0.95:   4.407 ms/op
                 listUser·p0.99:   5.718 ms/op
                 listUser·p0.999:  9.060 ms/op
                 listUser·p0.9999: 11.611 ms/op
                 listUser·p1.00:   12.386 ms/op

Iteration   2: 3.012 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.906 ms/op
                 listUser·p0.50:   2.945 ms/op
                 listUser·p0.90:   3.895 ms/op
                 listUser·p0.95:   4.432 ms/op
                 listUser·p0.99:   5.546 ms/op
                 listUser·p0.999:  9.025 ms/op
                 listUser·p0.9999: 10.404 ms/op
                 listUser·p1.00:   12.206 ms/op

Iteration   3: 3.021 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.729 ms/op
                 listUser·p0.50:   2.945 ms/op
                 listUser·p0.90:   3.957 ms/op
                 listUser·p0.95:   4.538 ms/op
                 listUser·p0.99:   5.808 ms/op
                 listUser·p0.999:  9.994 ms/op
                 listUser·p0.9999: 11.417 ms/op
                 listUser·p1.00:   12.009 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 318582
  mean =      3.011 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 147 
    [ 1.250,  2.500) = 94998 
    [ 2.500,  3.750) = 183035 
    [ 3.750,  5.000) = 32226 
    [ 5.000,  6.250) = 6663 
    [ 6.250,  7.500) = 812 
    [ 7.500,  8.750) = 250 
    [ 8.750, 10.000) = 268 
    [10.000, 11.250) = 139 
    [11.250, 12.500) = 44 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.729 ms/op
     p(50.0000) =      2.941 ms/op
     p(90.0000) =      3.912 ms/op
     p(95.0000) =      4.465 ms/op
     p(99.0000) =      5.702 ms/op
     p(99.9000) =      9.388 ms/op
     p(99.9900) =     11.359 ms/op
     p(99.9990) =     12.292 ms/op
     p(99.9999) =     12.386 ms/op
    p(100.0000) =     12.386 ms/op


# Run complete. Total time: 00:13:01

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.866 ± 0.594  ops/ms
ClientPb.existUser                       thrpt       3  13.016 ± 1.112  ops/ms
ClientPb.getUser                         thrpt       3  12.750 ± 0.940  ops/ms
ClientPb.listUser                        thrpt       3  10.678 ± 2.872  ops/ms
ClientPb.createUser                       avgt       3   2.474 ± 0.411   ms/op
ClientPb.existUser                        avgt       3   2.430 ± 0.148   ms/op
ClientPb.getUser                          avgt       3   2.487 ± 0.468   ms/op
ClientPb.listUser                         avgt       3   3.029 ± 0.218   ms/op
ClientPb.createUser                     sample  383757   2.499 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.818           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.548           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.035           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.166           ms/op
ClientPb.createUser:createUser·p0.99    sample           4.018           ms/op
ClientPb.createUser:createUser·p0.999   sample           7.958           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.828           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.975           ms/op
ClientPb.existUser                      sample  393392   2.438 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.710           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.490           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.957           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.068           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.723           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.524           ms/op
ClientPb.existUser:existUser·p0.9999    sample          14.292           ms/op
ClientPb.existUser:existUser·p1.00      sample          18.711           ms/op
ClientPb.getUser                        sample  386464   2.482 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.774           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.519           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.002           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.121           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.162           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.327           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.303           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.679           ms/op
ClientPb.listUser                       sample  318582   3.011 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.729           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.941           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.912           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.465           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.702           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.388           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.359           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.386           ms/op
