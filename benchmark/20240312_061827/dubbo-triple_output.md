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
# Warmup Iteration   1: 5.598 ops/ms
# Warmup Iteration   2: 12.310 ops/ms
# Warmup Iteration   3: 12.792 ops/ms
Iteration   1: 13.110 ops/ms
Iteration   2: 13.141 ops/ms
Iteration   3: 13.177 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  13.143 ±(99.9%) 0.609 ops/ms [Average]
  (min, avg, max) = (13.110, 13.143, 13.177), stdev = 0.033
  CI (99.9%): [12.534, 13.751] (assumes normal distribution)


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
# Warmup Iteration   1: 8.341 ops/ms
# Warmup Iteration   2: 13.369 ops/ms
# Warmup Iteration   3: 13.317 ops/ms
Iteration   1: 13.301 ops/ms
Iteration   2: 13.260 ops/ms
Iteration   3: 13.430 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.330 ±(99.9%) 1.618 ops/ms [Average]
  (min, avg, max) = (13.260, 13.330, 13.430), stdev = 0.089
  CI (99.9%): [11.712, 14.949] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:46
# Fork: 1 of 1
# Warmup Iteration   1: 8.280 ops/ms
# Warmup Iteration   2: 12.820 ops/ms
# Warmup Iteration   3: 13.165 ops/ms
Iteration   1: 13.169 ops/ms
Iteration   2: 13.255 ops/ms
Iteration   3: 13.140 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  13.188 ±(99.9%) 1.093 ops/ms [Average]
  (min, avg, max) = (13.140, 13.188, 13.255), stdev = 0.060
  CI (99.9%): [12.095, 14.281] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:44
# Fork: 1 of 1
# Warmup Iteration   1: 7.080 ops/ms
# Warmup Iteration   2: 10.742 ops/ms
# Warmup Iteration   3: 10.943 ops/ms
Iteration   1: 10.911 ops/ms
Iteration   2: 10.942 ops/ms
Iteration   3: 10.978 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.943 ±(99.9%) 0.615 ops/ms [Average]
  (min, avg, max) = (10.911, 10.943, 10.978), stdev = 0.034
  CI (99.9%): [10.328, 11.559] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:39
# Fork: 1 of 1
# Warmup Iteration   1: 4.185 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.543 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.472 ±(99.9%) 0.003 ms/op
Iteration   1: 2.490 ±(99.9%) 0.004 ms/op
Iteration   2: 2.461 ±(99.9%) 0.003 ms/op
Iteration   3: 2.457 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.469 ±(99.9%) 0.328 ms/op [Average]
  (min, avg, max) = (2.457, 2.469, 2.490), stdev = 0.018
  CI (99.9%): [2.141, 2.797] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:33
# Fork: 1 of 1
# Warmup Iteration   1: 3.610 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.375 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.393 ±(99.9%) 0.005 ms/op
Iteration   1: 2.370 ±(99.9%) 0.004 ms/op
Iteration   2: 2.384 ±(99.9%) 0.003 ms/op
Iteration   3: 2.376 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.377 ±(99.9%) 0.131 ms/op [Average]
  (min, avg, max) = (2.370, 2.377, 2.384), stdev = 0.007
  CI (99.9%): [2.245, 2.508] (assumes normal distribution)


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
# Warmup Iteration   1: 3.971 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.471 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.414 ±(99.9%) 0.004 ms/op
Iteration   1: 2.426 ±(99.9%) 0.004 ms/op
Iteration   2: 2.390 ±(99.9%) 0.005 ms/op
Iteration   3: 2.448 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.421 ±(99.9%) 0.541 ms/op [Average]
  (min, avg, max) = (2.390, 2.421, 2.448), stdev = 0.030
  CI (99.9%): [1.880, 2.962] (assumes normal distribution)


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
# Warmup Iteration   1: 4.475 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.963 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.933 ±(99.9%) 0.005 ms/op
Iteration   1: 2.975 ±(99.9%) 0.004 ms/op
Iteration   2: 2.928 ±(99.9%) 0.005 ms/op
Iteration   3: 2.917 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.940 ±(99.9%) 0.561 ms/op [Average]
  (min, avg, max) = (2.917, 2.940, 2.975), stdev = 0.031
  CI (99.9%): [2.379, 3.500] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:19
# Fork: 1 of 1
# Warmup Iteration   1: 4.059 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.535 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.436 ±(99.9%) 0.005 ms/op
Iteration   1: 2.441 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.861 ms/op
                 createUser·p0.50:   2.527 ms/op
                 createUser·p0.90:   2.957 ms/op
                 createUser·p0.95:   3.060 ms/op
                 createUser·p0.99:   3.576 ms/op
                 createUser·p0.999:  7.466 ms/op
                 createUser·p0.9999: 13.235 ms/op
                 createUser·p1.00:   13.533 ms/op

Iteration   2: 2.449 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.912 ms/op
                 createUser·p0.50:   2.544 ms/op
                 createUser·p0.90:   2.966 ms/op
                 createUser·p0.95:   3.076 ms/op
                 createUser·p0.99:   3.705 ms/op
                 createUser·p0.999:  10.027 ms/op
                 createUser·p0.9999: 11.649 ms/op
                 createUser·p1.00:   12.419 ms/op

Iteration   3: 2.468 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.371 ms/op
                 createUser·p0.50:   2.527 ms/op
                 createUser·p0.90:   2.990 ms/op
                 createUser·p0.95:   3.121 ms/op
                 createUser·p0.99:   4.055 ms/op
                 createUser·p0.999:  8.137 ms/op
                 createUser·p0.9999: 10.617 ms/op
                 createUser·p1.00:   10.830 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 391055
  mean =      2.453 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 56 
    [ 1.250,  2.500) = 192510 
    [ 2.500,  3.750) = 194478 
    [ 3.750,  5.000) = 3073 
    [ 5.000,  6.250) = 454 
    [ 6.250,  7.500) = 59 
    [ 7.500,  8.750) = 16 
    [ 8.750, 10.000) = 123 
    [10.000, 11.250) = 124 
    [11.250, 12.500) = 109 
    [12.500, 13.750) = 53 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.371 ms/op
     p(50.0000) =      2.531 ms/op
     p(90.0000) =      2.974 ms/op
     p(95.0000) =      3.084 ms/op
     p(99.0000) =      3.772 ms/op
     p(99.9000) =      9.126 ms/op
     p(99.9900) =     12.747 ms/op
     p(99.9990) =     13.468 ms/op
     p(99.9999) =     13.533 ms/op
    p(100.0000) =     13.533 ms/op


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
# Warmup Iteration   1: 3.606 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 2.415 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.431 ±(99.9%) 0.005 ms/op
Iteration   1: 2.415 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.029 ms/op
                 existUser·p0.50:   2.515 ms/op
                 existUser·p0.90:   2.925 ms/op
                 existUser·p0.95:   3.023 ms/op
                 existUser·p0.99:   3.514 ms/op
                 existUser·p0.999:  5.821 ms/op
                 existUser·p0.9999: 13.300 ms/op
                 existUser·p1.00:   13.992 ms/op

Iteration   2: 2.399 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.954 ms/op
                 existUser·p0.50:   2.519 ms/op
                 existUser·p0.90:   2.896 ms/op
                 existUser·p0.95:   2.982 ms/op
                 existUser·p0.99:   3.339 ms/op
                 existUser·p0.999:  5.967 ms/op
                 existUser·p0.9999: 13.042 ms/op
                 existUser·p1.00:   13.763 ms/op

Iteration   3: 2.424 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.949 ms/op
                 existUser·p0.50:   2.531 ms/op
                 existUser·p0.90:   2.937 ms/op
                 existUser·p0.95:   3.039 ms/op
                 existUser·p0.99:   3.495 ms/op
                 existUser·p0.999:  8.187 ms/op
                 existUser·p0.9999: 11.780 ms/op
                 existUser·p1.00:   11.993 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 397563
  mean =      2.413 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 44 
    [ 1.250,  2.500) = 196662 
    [ 2.500,  3.750) = 198350 
    [ 3.750,  5.000) = 1821 
    [ 5.000,  6.250) = 238 
    [ 6.250,  7.500) = 57 
    [ 7.500,  8.750) = 35 
    [ 8.750, 10.000) = 82 
    [10.000, 11.250) = 80 
    [11.250, 12.500) = 119 
    [12.500, 13.750) = 68 
    [13.750, 15.000) = 7 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.949 ms/op
     p(50.0000) =      2.523 ms/op
     p(90.0000) =      2.920 ms/op
     p(95.0000) =      3.015 ms/op
     p(99.0000) =      3.453 ms/op
     p(99.9000) =      7.265 ms/op
     p(99.9900) =     13.042 ms/op
     p(99.9990) =     13.878 ms/op
     p(99.9999) =     13.992 ms/op
    p(100.0000) =     13.992 ms/op


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
# Warmup Iteration   1: 3.625 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 2.512 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.469 ±(99.9%) 0.005 ms/op
Iteration   1: 2.462 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.851 ms/op
                 getUser·p0.50:   2.494 ms/op
                 getUser·p0.90:   2.982 ms/op
                 getUser·p0.95:   3.076 ms/op
                 getUser·p0.99:   3.625 ms/op
                 getUser·p0.999:  6.492 ms/op
                 getUser·p0.9999: 13.370 ms/op
                 getUser·p1.00:   13.648 ms/op

Iteration   2: 2.461 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.861 ms/op
                 getUser·p0.50:   2.494 ms/op
                 getUser·p0.90:   2.986 ms/op
                 getUser·p0.95:   3.092 ms/op
                 getUser·p0.99:   3.801 ms/op
                 getUser·p0.999:  7.465 ms/op
                 getUser·p0.9999: 13.288 ms/op
                 getUser·p1.00:   15.270 ms/op

Iteration   3: 2.479 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.867 ms/op
                 getUser·p0.50:   2.519 ms/op
                 getUser·p0.90:   3.006 ms/op
                 getUser·p0.95:   3.125 ms/op
                 getUser·p0.99:   3.822 ms/op
                 getUser·p0.999:  8.053 ms/op
                 getUser·p0.9999: 11.815 ms/op
                 getUser·p1.00:   14.172 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 388723
  mean =      2.468 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 73 
    [ 1.250,  2.500) = 194142 
    [ 2.500,  3.750) = 190579 
    [ 3.750,  5.000) = 3060 
    [ 5.000,  6.250) = 413 
    [ 6.250,  7.500) = 67 
    [ 7.500,  8.750) = 44 
    [ 8.750, 10.000) = 69 
    [10.000, 11.250) = 68 
    [11.250, 12.500) = 92 
    [12.500, 13.750) = 108 
    [13.750, 15.000) = 6 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.851 ms/op
     p(50.0000) =      2.503 ms/op
     p(90.0000) =      2.990 ms/op
     p(95.0000) =      3.097 ms/op
     p(99.0000) =      3.756 ms/op
     p(99.9000) =      7.642 ms/op
     p(99.9900) =     13.240 ms/op
     p(99.9990) =     14.586 ms/op
     p(99.9999) =     15.270 ms/op
    p(100.0000) =     15.270 ms/op


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
# Warmup Iteration   1: 4.815 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 3.008 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.973 ±(99.9%) 0.009 ms/op
Iteration   1: 2.961 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.851 ms/op
                 listUser·p0.50:   2.900 ms/op
                 listUser·p0.90:   3.858 ms/op
                 listUser·p0.95:   4.358 ms/op
                 listUser·p0.99:   5.546 ms/op
                 listUser·p0.999:  8.978 ms/op
                 listUser·p0.9999: 11.004 ms/op
                 listUser·p1.00:   11.354 ms/op

Iteration   2: 2.969 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.805 ms/op
                 listUser·p0.50:   2.908 ms/op
                 listUser·p0.90:   3.842 ms/op
                 listUser·p0.95:   4.375 ms/op
                 listUser·p0.99:   5.546 ms/op
                 listUser·p0.999:  9.470 ms/op
                 listUser·p0.9999: 11.731 ms/op
                 listUser·p1.00:   12.042 ms/op

Iteration   3: 2.963 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.843 ms/op
                 listUser·p0.50:   2.892 ms/op
                 listUser·p0.90:   3.895 ms/op
                 listUser·p0.95:   4.424 ms/op
                 listUser·p0.99:   5.677 ms/op
                 listUser·p0.999:  9.608 ms/op
                 listUser·p0.9999: 11.308 ms/op
                 listUser·p1.00:   12.157 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 323470
  mean =      2.965 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 176 
    [ 1.250,  2.500) = 104667 
    [ 2.500,  3.750) = 180710 
    [ 3.750,  5.000) = 30410 
    [ 5.000,  6.250) = 6230 
    [ 6.250,  7.500) = 628 
    [ 7.500,  8.750) = 223 
    [ 8.750, 10.000) = 204 
    [10.000, 11.250) = 180 
    [11.250, 12.500) = 42 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.805 ms/op
     p(50.0000) =      2.900 ms/op
     p(90.0000) =      3.867 ms/op
     p(95.0000) =      4.383 ms/op
     p(99.0000) =      5.595 ms/op
     p(99.9000) =      9.298 ms/op
     p(99.9900) =     11.408 ms/op
     p(99.9990) =     11.867 ms/op
     p(99.9999) =     12.157 ms/op
    p(100.0000) =     12.157 ms/op


# Run complete. Total time: 00:12:57

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  13.143 ± 0.609  ops/ms
ClientPb.existUser                       thrpt       3  13.330 ± 1.618  ops/ms
ClientPb.getUser                         thrpt       3  13.188 ± 1.093  ops/ms
ClientPb.listUser                        thrpt       3  10.943 ± 0.615  ops/ms
ClientPb.createUser                       avgt       3   2.469 ± 0.328   ms/op
ClientPb.existUser                        avgt       3   2.377 ± 0.131   ms/op
ClientPb.getUser                          avgt       3   2.421 ± 0.541   ms/op
ClientPb.listUser                         avgt       3   2.940 ± 0.561   ms/op
ClientPb.createUser                     sample  391055   2.453 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.371           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.531           ms/op
ClientPb.createUser:createUser·p0.90    sample           2.974           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.084           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.772           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.126           ms/op
ClientPb.createUser:createUser·p0.9999  sample          12.747           ms/op
ClientPb.createUser:createUser·p1.00    sample          13.533           ms/op
ClientPb.existUser                      sample  397563   2.413 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.949           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.523           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.920           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.015           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.453           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.265           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.042           ms/op
ClientPb.existUser:existUser·p1.00      sample          13.992           ms/op
ClientPb.getUser                        sample  388723   2.468 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.851           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.503           ms/op
ClientPb.getUser:getUser·p0.90          sample           2.990           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.097           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.756           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.642           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.240           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.270           ms/op
ClientPb.listUser                       sample  323470   2.965 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.805           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.900           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.867           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.383           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.595           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.298           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.408           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.157           ms/op
