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
# Warmup Iteration   1: 5.152 ops/ms
# Warmup Iteration   2: 12.149 ops/ms
# Warmup Iteration   3: 12.473 ops/ms
Iteration   1: 12.708 ops/ms
Iteration   2: 12.684 ops/ms
Iteration   3: 12.930 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.774 ±(99.9%) 2.476 ops/ms [Average]
  (min, avg, max) = (12.684, 12.774, 12.930), stdev = 0.136
  CI (99.9%): [10.298, 15.250] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:52
# Fork: 1 of 1
# Warmup Iteration   1: 8.495 ops/ms
# Warmup Iteration   2: 13.286 ops/ms
# Warmup Iteration   3: 13.240 ops/ms
Iteration   1: 13.199 ops/ms
Iteration   2: 13.175 ops/ms
Iteration   3: 13.232 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.202 ±(99.9%) 0.523 ops/ms [Average]
  (min, avg, max) = (13.175, 13.202, 13.232), stdev = 0.029
  CI (99.9%): [12.679, 13.725] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.721 ops/ms
# Warmup Iteration   2: 12.577 ops/ms
# Warmup Iteration   3: 12.451 ops/ms
Iteration   1: 12.777 ops/ms
Iteration   2: 12.721 ops/ms
Iteration   3: 12.763 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.754 ±(99.9%) 0.525 ops/ms [Average]
  (min, avg, max) = (12.721, 12.754, 12.777), stdev = 0.029
  CI (99.9%): [12.229, 13.278] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:45
# Fork: 1 of 1
# Warmup Iteration   1: 6.928 ops/ms
# Warmup Iteration   2: 10.716 ops/ms
# Warmup Iteration   3: 10.773 ops/ms
Iteration   1: 10.725 ops/ms
Iteration   2: 10.734 ops/ms
Iteration   3: 10.734 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.731 ±(99.9%) 0.093 ops/ms [Average]
  (min, avg, max) = (10.725, 10.731, 10.734), stdev = 0.005
  CI (99.9%): [10.638, 10.824] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:39
# Fork: 1 of 1
# Warmup Iteration   1: 3.933 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.534 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.507 ±(99.9%) 0.004 ms/op
Iteration   1: 2.492 ±(99.9%) 0.005 ms/op
Iteration   2: 2.529 ±(99.9%) 0.004 ms/op
Iteration   3: 2.493 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.505 ±(99.9%) 0.392 ms/op [Average]
  (min, avg, max) = (2.492, 2.505, 2.529), stdev = 0.021
  CI (99.9%): [2.113, 2.897] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:34
# Fork: 1 of 1
# Warmup Iteration   1: 3.589 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.494 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.469 ±(99.9%) 0.005 ms/op
Iteration   1: 2.566 ±(99.9%) 0.004 ms/op
Iteration   2: 2.664 ±(99.9%) 0.004 ms/op
Iteration   3: 2.547 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.592 ±(99.9%) 1.145 ms/op [Average]
  (min, avg, max) = (2.547, 2.592, 2.664), stdev = 0.063
  CI (99.9%): [1.448, 3.737] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:28
# Fork: 1 of 1
# Warmup Iteration   1: 4.123 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.648 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.607 ±(99.9%) 0.004 ms/op
Iteration   1: 2.590 ±(99.9%) 0.004 ms/op
Iteration   2: 2.585 ±(99.9%) 0.005 ms/op
Iteration   3: 2.541 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.572 ±(99.9%) 0.488 ms/op [Average]
  (min, avg, max) = (2.541, 2.572, 2.590), stdev = 0.027
  CI (99.9%): [2.084, 3.060] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:24
# Fork: 1 of 1
# Warmup Iteration   1: 5.254 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.070 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.117 ±(99.9%) 0.004 ms/op
Iteration   1: 3.027 ±(99.9%) 0.005 ms/op
Iteration   2: 2.993 ±(99.9%) 0.005 ms/op
Iteration   3: 2.972 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.997 ±(99.9%) 0.503 ms/op [Average]
  (min, avg, max) = (2.972, 2.997, 3.027), stdev = 0.028
  CI (99.9%): [2.495, 3.500] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:19
# Fork: 1 of 1
# Warmup Iteration   1: 4.019 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.644 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.514 ±(99.9%) 0.005 ms/op
Iteration   1: 2.514 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.660 ms/op
                 createUser·p0.50:   2.613 ms/op
                 createUser·p0.90:   3.035 ms/op
                 createUser·p0.95:   3.146 ms/op
                 createUser·p0.99:   3.777 ms/op
                 createUser·p0.999:  10.060 ms/op
                 createUser·p0.9999: 13.353 ms/op
                 createUser·p1.00:   14.238 ms/op

Iteration   2: 2.485 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.955 ms/op
                 createUser·p0.50:   2.605 ms/op
                 createUser·p0.90:   3.002 ms/op
                 createUser·p0.95:   3.088 ms/op
                 createUser·p0.99:   3.445 ms/op
                 createUser·p0.999:  8.379 ms/op
                 createUser·p0.9999: 12.648 ms/op
                 createUser·p1.00:   12.894 ms/op

Iteration   3: 2.510 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.044 ms/op
                 createUser·p0.50:   2.601 ms/op
                 createUser·p0.90:   3.039 ms/op
                 createUser·p0.95:   3.158 ms/op
                 createUser·p0.99:   3.879 ms/op
                 createUser·p0.999:  7.668 ms/op
                 createUser·p0.9999: 11.654 ms/op
                 createUser·p1.00:   17.990 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 383057
  mean =      2.503 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 32 
    [ 1.250,  2.500) = 183807 
    [ 2.500,  3.750) = 195666 
    [ 3.750,  5.000) = 2488 
    [ 5.000,  6.250) = 605 
    [ 6.250,  7.500) = 70 
    [ 7.500,  8.750) = 53 
    [ 8.750, 10.000) = 43 
    [10.000, 11.250) = 95 
    [11.250, 12.500) = 121 
    [12.500, 13.750) = 70 
    [13.750, 15.000) = 5 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.660 ms/op
     p(50.0000) =      2.605 ms/op
     p(90.0000) =      3.027 ms/op
     p(95.0000) =      3.129 ms/op
     p(99.0000) =      3.703 ms/op
     p(99.9000) =      7.668 ms/op
     p(99.9900) =     12.824 ms/op
     p(99.9990) =     14.343 ms/op
     p(99.9999) =     17.990 ms/op
    p(100.0000) =     17.990 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.586 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 2.437 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.459 ±(99.9%) 0.005 ms/op
Iteration   1: 2.455 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.856 ms/op
                 existUser·p0.50:   2.523 ms/op
                 existUser·p0.90:   3.002 ms/op
                 existUser·p0.95:   3.129 ms/op
                 existUser·p0.99:   3.617 ms/op
                 existUser·p0.999:  11.453 ms/op
                 existUser·p0.9999: 13.189 ms/op
                 existUser·p1.00:   13.746 ms/op

Iteration   2: 2.572 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.016 ms/op
                 existUser·p0.50:   2.613 ms/op
                 existUser·p0.90:   3.117 ms/op
                 existUser·p0.95:   3.240 ms/op
                 existUser·p0.99:   3.994 ms/op
                 existUser·p0.999:  12.026 ms/op
                 existUser·p0.9999: 13.954 ms/op
                 existUser·p1.00:   16.073 ms/op

Iteration   3: 2.633 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.995 ms/op
                 existUser·p0.50:   2.634 ms/op
                 existUser·p0.90:   3.150 ms/op
                 existUser·p0.95:   3.367 ms/op
                 existUser·p0.99:   5.808 ms/op
                 existUser·p0.999:  13.337 ms/op
                 existUser·p0.9999: 15.745 ms/op
                 existUser·p1.00:   17.727 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 375949
  mean =      2.551 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 47 
    [ 1.250,  2.500) = 181384 
    [ 2.500,  3.750) = 188375 
    [ 3.750,  5.000) = 3499 
    [ 5.000,  6.250) = 970 
    [ 6.250,  7.500) = 400 
    [ 7.500,  8.750) = 222 
    [ 8.750, 10.000) = 226 
    [10.000, 11.250) = 206 
    [11.250, 12.500) = 304 
    [12.500, 13.750) = 228 
    [13.750, 15.000) = 63 
    [15.000, 16.250) = 17 
    [16.250, 17.500) = 7 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.856 ms/op
     p(50.0000) =      2.580 ms/op
     p(90.0000) =      3.097 ms/op
     p(95.0000) =      3.236 ms/op
     p(99.0000) =      4.391 ms/op
     p(99.9000) =     12.304 ms/op
     p(99.9900) =     14.752 ms/op
     p(99.9990) =     16.693 ms/op
     p(99.9999) =     17.727 ms/op
    p(100.0000) =     17.727 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:09
# Fork: 1 of 1
# Warmup Iteration   1: 4.393 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 2.709 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.628 ±(99.9%) 0.007 ms/op
Iteration   1: 2.607 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.727 ms/op
                 getUser·p0.50:   2.572 ms/op
                 getUser·p0.90:   3.199 ms/op
                 getUser·p0.95:   3.400 ms/op
                 getUser·p0.99:   4.661 ms/op
                 getUser·p0.999:  12.966 ms/op
                 getUser·p0.9999: 15.450 ms/op
                 getUser·p1.00:   16.122 ms/op

Iteration   2: 2.624 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.928 ms/op
                 getUser·p0.50:   2.621 ms/op
                 getUser·p0.90:   3.199 ms/op
                 getUser·p0.95:   3.498 ms/op
                 getUser·p0.99:   4.899 ms/op
                 getUser·p0.999:  12.272 ms/op
                 getUser·p0.9999: 15.690 ms/op
                 getUser·p1.00:   18.678 ms/op

Iteration   3: 2.654 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.993 ms/op
                 getUser·p0.50:   2.638 ms/op
                 getUser·p0.90:   3.219 ms/op
                 getUser·p0.95:   3.518 ms/op
                 getUser·p0.99:   5.661 ms/op
                 getUser·p0.999:  11.020 ms/op
                 getUser·p0.9999: 13.416 ms/op
                 getUser·p1.00:   14.090 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 364817
  mean =      2.629 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 67 
    [ 1.250,  2.500) = 171566 
    [ 2.500,  3.750) = 181392 
    [ 3.750,  5.000) = 8040 
    [ 5.000,  6.250) = 1923 
    [ 6.250,  7.500) = 789 
    [ 7.500,  8.750) = 303 
    [ 8.750, 10.000) = 174 
    [10.000, 11.250) = 141 
    [11.250, 12.500) = 141 
    [12.500, 13.750) = 136 
    [13.750, 15.000) = 85 
    [15.000, 16.250) = 55 
    [16.250, 17.500) = 2 
    [17.500, 18.750) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.727 ms/op
     p(50.0000) =      2.609 ms/op
     p(90.0000) =      3.207 ms/op
     p(95.0000) =      3.461 ms/op
     p(99.0000) =      5.038 ms/op
     p(99.9000) =     11.583 ms/op
     p(99.9900) =     15.409 ms/op
     p(99.9990) =     17.018 ms/op
     p(99.9999) =     18.678 ms/op
    p(100.0000) =     18.678 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 5.189 ±(99.9%) 0.073 ms/op
# Warmup Iteration   2: 3.215 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.119 ±(99.9%) 0.010 ms/op
Iteration   1: 3.106 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.873 ms/op
                 listUser·p0.50:   3.011 ms/op
                 listUser·p0.90:   3.985 ms/op
                 listUser·p0.95:   4.571 ms/op
                 listUser·p0.99:   6.193 ms/op
                 listUser·p0.999:  10.356 ms/op
                 listUser·p0.9999: 13.904 ms/op
                 listUser·p1.00:   16.171 ms/op

Iteration   2: 3.054 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.888 ms/op
                 listUser·p0.50:   2.970 ms/op
                 listUser·p0.90:   3.936 ms/op
                 listUser·p0.95:   4.481 ms/op
                 listUser·p0.99:   5.849 ms/op
                 listUser·p0.999:  11.572 ms/op
                 listUser·p0.9999: 15.984 ms/op
                 listUser·p1.00:   18.678 ms/op

Iteration   3: 2.987 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.860 ms/op
                 listUser·p0.50:   2.933 ms/op
                 listUser·p0.90:   3.813 ms/op
                 listUser·p0.95:   4.293 ms/op
                 listUser·p0.99:   5.554 ms/op
                 listUser·p0.999:  9.650 ms/op
                 listUser·p0.9999: 12.147 ms/op
                 listUser·p1.00:   12.927 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 314621
  mean =      3.048 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 123 
    [ 1.250,  2.500) = 85464 
    [ 2.500,  3.750) = 188453 
    [ 3.750,  5.000) = 32504 
    [ 5.000,  6.250) = 5859 
    [ 6.250,  7.500) = 1069 
    [ 7.500,  8.750) = 427 
    [ 8.750, 10.000) = 299 
    [10.000, 11.250) = 237 
    [11.250, 12.500) = 87 
    [12.500, 13.750) = 61 
    [13.750, 15.000) = 20 
    [15.000, 16.250) = 10 
    [16.250, 17.500) = 6 
    [17.500, 18.750) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.860 ms/op
     p(50.0000) =      2.970 ms/op
     p(90.0000) =      3.912 ms/op
     p(95.0000) =      4.440 ms/op
     p(99.0000) =      5.839 ms/op
     p(99.9000) =     10.404 ms/op
     p(99.9900) =     13.935 ms/op
     p(99.9990) =     17.297 ms/op
     p(99.9999) =     18.678 ms/op
    p(100.0000) =     18.678 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.774 ± 2.476  ops/ms
ClientPb.existUser                       thrpt       3  13.202 ± 0.523  ops/ms
ClientPb.getUser                         thrpt       3  12.754 ± 0.525  ops/ms
ClientPb.listUser                        thrpt       3  10.731 ± 0.093  ops/ms
ClientPb.createUser                       avgt       3   2.505 ± 0.392   ms/op
ClientPb.existUser                        avgt       3   2.592 ± 1.145   ms/op
ClientPb.getUser                          avgt       3   2.572 ± 0.488   ms/op
ClientPb.listUser                         avgt       3   2.997 ± 0.503   ms/op
ClientPb.createUser                     sample  383057   2.503 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.660           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.605           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.027           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.129           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.703           ms/op
ClientPb.createUser:createUser·p0.999   sample           7.668           ms/op
ClientPb.createUser:createUser·p0.9999  sample          12.824           ms/op
ClientPb.createUser:createUser·p1.00    sample          17.990           ms/op
ClientPb.existUser                      sample  375949   2.551 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.856           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.580           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.097           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.236           ms/op
ClientPb.existUser:existUser·p0.99      sample           4.391           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.304           ms/op
ClientPb.existUser:existUser·p0.9999    sample          14.752           ms/op
ClientPb.existUser:existUser·p1.00      sample          17.727           ms/op
ClientPb.getUser                        sample  364817   2.629 ± 0.004   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.727           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.609           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.207           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.461           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.038           ms/op
ClientPb.getUser:getUser·p0.999         sample          11.583           ms/op
ClientPb.getUser:getUser·p0.9999        sample          15.409           ms/op
ClientPb.getUser:getUser·p1.00          sample          18.678           ms/op
ClientPb.listUser                       sample  314621   3.048 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.860           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.970           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.912           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.440           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.839           ms/op
ClientPb.listUser:listUser·p0.999       sample          10.404           ms/op
ClientPb.listUser:listUser·p0.9999      sample          13.935           ms/op
ClientPb.listUser:listUser·p1.00        sample          18.678           ms/op
