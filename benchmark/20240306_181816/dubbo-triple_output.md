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
# Warmup Iteration   1: 4.557 ops/ms
# Warmup Iteration   2: 11.879 ops/ms
# Warmup Iteration   3: 12.578 ops/ms
Iteration   1: 12.709 ops/ms
Iteration   2: 12.823 ops/ms
Iteration   3: 12.966 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.833 ±(99.9%) 2.354 ops/ms [Average]
  (min, avg, max) = (12.709, 12.833, 12.966), stdev = 0.129
  CI (99.9%): [10.479, 15.187] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:01
# Fork: 1 of 1
# Warmup Iteration   1: 8.583 ops/ms
# Warmup Iteration   2: 13.357 ops/ms
# Warmup Iteration   3: 13.216 ops/ms
Iteration   1: 13.350 ops/ms
Iteration   2: 13.360 ops/ms
Iteration   3: 13.202 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.304 ±(99.9%) 1.613 ops/ms [Average]
  (min, avg, max) = (13.202, 13.304, 13.360), stdev = 0.088
  CI (99.9%): [11.690, 14.917] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.867 ops/ms
# Warmup Iteration   2: 13.036 ops/ms
# Warmup Iteration   3: 13.092 ops/ms
Iteration   1: 13.264 ops/ms
Iteration   2: 13.091 ops/ms
Iteration   3: 13.197 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  13.184 ±(99.9%) 1.591 ops/ms [Average]
  (min, avg, max) = (13.091, 13.184, 13.264), stdev = 0.087
  CI (99.9%): [11.594, 14.775] (assumes normal distribution)


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
# Warmup Iteration   1: 6.986 ops/ms
# Warmup Iteration   2: 10.623 ops/ms
# Warmup Iteration   3: 10.515 ops/ms
Iteration   1: 10.519 ops/ms
Iteration   2: 10.632 ops/ms
Iteration   3: 10.579 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.577 ±(99.9%) 1.025 ops/ms [Average]
  (min, avg, max) = (10.519, 10.577, 10.632), stdev = 0.056
  CI (99.9%): [9.552, 11.602] (assumes normal distribution)


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
# Warmup Iteration   1: 4.034 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.590 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.509 ±(99.9%) 0.004 ms/op
Iteration   1: 2.456 ±(99.9%) 0.004 ms/op
Iteration   2: 2.475 ±(99.9%) 0.004 ms/op
Iteration   3: 2.468 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.466 ±(99.9%) 0.181 ms/op [Average]
  (min, avg, max) = (2.456, 2.466, 2.475), stdev = 0.010
  CI (99.9%): [2.285, 2.647] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:34
# Fork: 1 of 1
# Warmup Iteration   1: 3.904 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.466 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.463 ±(99.9%) 0.003 ms/op
Iteration   1: 2.471 ±(99.9%) 0.003 ms/op
Iteration   2: 2.458 ±(99.9%) 0.004 ms/op
Iteration   3: 2.465 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.465 ±(99.9%) 0.123 ms/op [Average]
  (min, avg, max) = (2.458, 2.465, 2.471), stdev = 0.007
  CI (99.9%): [2.342, 2.587] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:29
# Fork: 1 of 1
# Warmup Iteration   1: 3.746 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.459 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.436 ±(99.9%) 0.003 ms/op
Iteration   1: 2.439 ±(99.9%) 0.004 ms/op
Iteration   2: 2.423 ±(99.9%) 0.004 ms/op
Iteration   3: 2.410 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.424 ±(99.9%) 0.271 ms/op [Average]
  (min, avg, max) = (2.410, 2.424, 2.439), stdev = 0.015
  CI (99.9%): [2.153, 2.695] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:24
# Fork: 1 of 1
# Warmup Iteration   1: 4.769 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.021 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.970 ±(99.9%) 0.006 ms/op
Iteration   1: 2.964 ±(99.9%) 0.006 ms/op
Iteration   2: 2.949 ±(99.9%) 0.006 ms/op
Iteration   3: 2.953 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.955 ±(99.9%) 0.139 ms/op [Average]
  (min, avg, max) = (2.949, 2.955, 2.964), stdev = 0.008
  CI (99.9%): [2.817, 3.094] (assumes normal distribution)


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
# Warmup Iteration   1: 4.124 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.621 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.490 ±(99.9%) 0.005 ms/op
Iteration   1: 2.486 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.696 ms/op
                 createUser·p0.50:   2.523 ms/op
                 createUser·p0.90:   3.015 ms/op
                 createUser·p0.95:   3.146 ms/op
                 createUser·p0.99:   3.744 ms/op
                 createUser·p0.999:  11.682 ms/op
                 createUser·p0.9999: 22.086 ms/op
                 createUser·p1.00:   22.872 ms/op

Iteration   2: 2.484 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.930 ms/op
                 createUser·p0.50:   2.527 ms/op
                 createUser·p0.90:   3.011 ms/op
                 createUser·p0.95:   3.109 ms/op
                 createUser·p0.99:   3.437 ms/op
                 createUser·p0.999:  10.846 ms/op
                 createUser·p0.9999: 14.418 ms/op
                 createUser·p1.00:   14.844 ms/op

Iteration   3: 2.520 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.941 ms/op
                 createUser·p0.50:   2.576 ms/op
                 createUser·p0.90:   3.068 ms/op
                 createUser·p0.95:   3.199 ms/op
                 createUser·p0.99:   3.895 ms/op
                 createUser·p0.999:  8.290 ms/op
                 createUser·p0.9999: 10.666 ms/op
                 createUser·p1.00:   11.485 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 384083
  mean =      2.497 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 188597 
    [ 2.500,  5.000) = 194610 
    [ 5.000,  7.500) = 353 
    [ 7.500, 10.000) = 149 
    [10.000, 12.500) = 205 
    [12.500, 15.000) = 137 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.696 ms/op
     p(50.0000) =      2.540 ms/op
     p(90.0000) =      3.031 ms/op
     p(95.0000) =      3.150 ms/op
     p(99.0000) =      3.711 ms/op
     p(99.9000) =      9.911 ms/op
     p(99.9900) =     14.804 ms/op
     p(99.9990) =     22.751 ms/op
     p(99.9999) =     22.872 ms/op
    p(100.0000) =     22.872 ms/op


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
# Warmup Iteration   1: 3.804 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.417 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.378 ±(99.9%) 0.005 ms/op
Iteration   1: 2.364 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.908 ms/op
                 existUser·p0.50:   2.437 ms/op
                 existUser·p0.90:   2.863 ms/op
                 existUser·p0.95:   2.961 ms/op
                 existUser·p0.99:   3.510 ms/op
                 existUser·p0.999:  6.445 ms/op
                 existUser·p0.9999: 13.738 ms/op
                 existUser·p1.00:   14.369 ms/op

Iteration   2: 2.385 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.866 ms/op
                 existUser·p0.50:   2.400 ms/op
                 existUser·p0.90:   2.904 ms/op
                 existUser·p0.95:   3.019 ms/op
                 existUser·p0.99:   3.670 ms/op
                 existUser·p0.999:  7.017 ms/op
                 existUser·p0.9999: 12.494 ms/op
                 existUser·p1.00:   12.911 ms/op

Iteration   3: 2.361 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.825 ms/op
                 existUser·p0.50:   2.404 ms/op
                 existUser·p0.90:   2.867 ms/op
                 existUser·p0.95:   2.982 ms/op
                 existUser·p0.99:   3.600 ms/op
                 existUser·p0.999:  7.846 ms/op
                 existUser·p0.9999: 11.436 ms/op
                 existUser·p1.00:   12.993 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 404589
  mean =      2.370 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 81 
    [ 1.250,  2.500) = 214517 
    [ 2.500,  3.750) = 186821 
    [ 3.750,  5.000) = 2314 
    [ 5.000,  6.250) = 391 
    [ 6.250,  7.500) = 66 
    [ 7.500,  8.750) = 31 
    [ 8.750, 10.000) = 78 
    [10.000, 11.250) = 90 
    [11.250, 12.500) = 87 
    [12.500, 13.750) = 101 
    [13.750, 15.000) = 12 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.825 ms/op
     p(50.0000) =      2.413 ms/op
     p(90.0000) =      2.879 ms/op
     p(95.0000) =      2.990 ms/op
     p(99.0000) =      3.588 ms/op
     p(99.9000) =      7.313 ms/op
     p(99.9900) =     13.402 ms/op
     p(99.9990) =     14.073 ms/op
     p(99.9999) =     14.369 ms/op
    p(100.0000) =     14.369 ms/op


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
# Warmup Iteration   1: 3.677 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.515 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.470 ±(99.9%) 0.005 ms/op
Iteration   1: 2.496 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.997 ms/op
                 getUser·p0.50:   2.507 ms/op
                 getUser·p0.90:   3.039 ms/op
                 getUser·p0.95:   3.174 ms/op
                 getUser·p0.99:   3.871 ms/op
                 getUser·p0.999:  11.079 ms/op
                 getUser·p0.9999: 13.684 ms/op
                 getUser·p1.00:   14.008 ms/op

Iteration   2: 2.499 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.924 ms/op
                 getUser·p0.50:   2.515 ms/op
                 getUser·p0.90:   3.047 ms/op
                 getUser·p0.95:   3.203 ms/op
                 getUser·p0.99:   4.174 ms/op
                 getUser·p0.999:  6.366 ms/op
                 getUser·p0.9999: 12.832 ms/op
                 getUser·p1.00:   13.025 ms/op

Iteration   3: 2.477 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.858 ms/op
                 getUser·p0.50:   2.503 ms/op
                 getUser·p0.90:   3.027 ms/op
                 getUser·p0.95:   3.162 ms/op
                 getUser·p0.99:   3.871 ms/op
                 getUser·p0.999:  6.093 ms/op
                 getUser·p0.9999: 11.619 ms/op
                 getUser·p1.00:   12.567 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 385119
  mean =      2.490 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 94 
    [ 1.250,  2.500) = 191841 
    [ 2.500,  3.750) = 187819 
    [ 3.750,  5.000) = 4433 
    [ 5.000,  6.250) = 543 
    [ 6.250,  7.500) = 37 
    [ 7.500,  8.750) = 21 
    [ 8.750, 10.000) = 58 
    [10.000, 11.250) = 94 
    [11.250, 12.500) = 91 
    [12.500, 13.750) = 78 
    [13.750, 15.000) = 10 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.858 ms/op
     p(50.0000) =      2.507 ms/op
     p(90.0000) =      3.039 ms/op
     p(95.0000) =      3.178 ms/op
     p(99.0000) =      3.961 ms/op
     p(99.9000) =      6.363 ms/op
     p(99.9900) =     13.361 ms/op
     p(99.9990) =     13.945 ms/op
     p(99.9999) =     14.008 ms/op
    p(100.0000) =     14.008 ms/op


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
# Warmup Iteration   1: 4.721 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.033 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.963 ±(99.9%) 0.009 ms/op
Iteration   1: 2.980 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.590 ms/op
                 listUser·p0.50:   2.908 ms/op
                 listUser·p0.90:   3.895 ms/op
                 listUser·p0.95:   4.415 ms/op
                 listUser·p0.99:   5.612 ms/op
                 listUser·p0.999:  9.039 ms/op
                 listUser·p0.9999: 11.522 ms/op
                 listUser·p1.00:   12.714 ms/op

Iteration   2: 2.977 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.822 ms/op
                 listUser·p0.50:   2.908 ms/op
                 listUser·p0.90:   3.854 ms/op
                 listUser·p0.95:   4.375 ms/op
                 listUser·p0.99:   5.587 ms/op
                 listUser·p0.999:  9.103 ms/op
                 listUser·p0.9999: 11.113 ms/op
                 listUser·p1.00:   11.289 ms/op

Iteration   3: 2.974 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.837 ms/op
                 listUser·p0.50:   2.904 ms/op
                 listUser·p0.90:   3.883 ms/op
                 listUser·p0.95:   4.412 ms/op
                 listUser·p0.99:   5.562 ms/op
                 listUser·p0.999:  9.789 ms/op
                 listUser·p0.9999: 11.014 ms/op
                 listUser·p1.00:   13.468 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 322194
  mean =      2.977 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 171 
    [ 1.250,  2.500) = 99326 
    [ 2.500,  3.750) = 184066 
    [ 3.750,  5.000) = 31065 
    [ 5.000,  6.250) = 6130 
    [ 6.250,  7.500) = 744 
    [ 7.500,  8.750) = 260 
    [ 8.750, 10.000) = 262 
    [10.000, 11.250) = 143 
    [11.250, 12.500) = 20 
    [12.500, 13.750) = 7 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.590 ms/op
     p(50.0000) =      2.908 ms/op
     p(90.0000) =      3.879 ms/op
     p(95.0000) =      4.399 ms/op
     p(99.0000) =      5.595 ms/op
     p(99.9000) =      9.257 ms/op
     p(99.9900) =     11.207 ms/op
     p(99.9990) =     13.384 ms/op
     p(99.9999) =     13.468 ms/op
    p(100.0000) =     13.468 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.833 ± 2.354  ops/ms
ClientPb.existUser                       thrpt       3  13.304 ± 1.613  ops/ms
ClientPb.getUser                         thrpt       3  13.184 ± 1.591  ops/ms
ClientPb.listUser                        thrpt       3  10.577 ± 1.025  ops/ms
ClientPb.createUser                       avgt       3   2.466 ± 0.181   ms/op
ClientPb.existUser                        avgt       3   2.465 ± 0.123   ms/op
ClientPb.getUser                          avgt       3   2.424 ± 0.271   ms/op
ClientPb.listUser                         avgt       3   2.955 ± 0.139   ms/op
ClientPb.createUser                     sample  384083   2.497 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.696           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.540           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.031           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.150           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.711           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.911           ms/op
ClientPb.createUser:createUser·p0.9999  sample          14.804           ms/op
ClientPb.createUser:createUser·p1.00    sample          22.872           ms/op
ClientPb.existUser                      sample  404589   2.370 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.825           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.413           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.879           ms/op
ClientPb.existUser:existUser·p0.95      sample           2.990           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.588           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.313           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.402           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.369           ms/op
ClientPb.getUser                        sample  385119   2.490 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.858           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.507           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.039           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.178           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.961           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.363           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.361           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.008           ms/op
ClientPb.listUser                       sample  322194   2.977 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.590           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.908           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.879           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.399           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.595           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.257           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.207           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.468           ms/op
