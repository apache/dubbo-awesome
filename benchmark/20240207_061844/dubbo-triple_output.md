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
# Warmup Iteration   1: 4.757 ops/ms
# Warmup Iteration   2: 12.146 ops/ms
# Warmup Iteration   3: 12.225 ops/ms
Iteration   1: 12.663 ops/ms
Iteration   2: 12.624 ops/ms
Iteration   3: 12.754 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.680 ±(99.9%) 1.217 ops/ms [Average]
  (min, avg, max) = (12.624, 12.680, 12.754), stdev = 0.067
  CI (99.9%): [11.464, 13.897] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:53
# Fork: 1 of 1
# Warmup Iteration   1: 7.794 ops/ms
# Warmup Iteration   2: 12.960 ops/ms
# Warmup Iteration   3: 13.087 ops/ms
Iteration   1: 12.982 ops/ms
Iteration   2: 13.162 ops/ms
Iteration   3: 13.087 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.077 ±(99.9%) 1.652 ops/ms [Average]
  (min, avg, max) = (12.982, 13.077, 13.162), stdev = 0.091
  CI (99.9%): [11.425, 14.729] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.551 ops/ms
# Warmup Iteration   2: 12.370 ops/ms
# Warmup Iteration   3: 12.746 ops/ms
Iteration   1: 12.626 ops/ms
Iteration   2: 12.790 ops/ms
Iteration   3: 12.714 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.710 ±(99.9%) 1.500 ops/ms [Average]
  (min, avg, max) = (12.626, 12.710, 12.790), stdev = 0.082
  CI (99.9%): [11.210, 14.210] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:45
# Fork: 1 of 1
# Warmup Iteration   1: 6.490 ops/ms
# Warmup Iteration   2: 10.638 ops/ms
# Warmup Iteration   3: 10.723 ops/ms
Iteration   1: 10.781 ops/ms
Iteration   2: 10.718 ops/ms
Iteration   3: 10.767 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.755 ±(99.9%) 0.599 ops/ms [Average]
  (min, avg, max) = (10.718, 10.755, 10.781), stdev = 0.033
  CI (99.9%): [10.156, 11.355] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:40
# Fork: 1 of 1
# Warmup Iteration   1: 4.133 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.586 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.528 ±(99.9%) 0.004 ms/op
Iteration   1: 2.542 ±(99.9%) 0.005 ms/op
Iteration   2: 2.512 ±(99.9%) 0.005 ms/op
Iteration   3: 2.498 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.517 ±(99.9%) 0.413 ms/op [Average]
  (min, avg, max) = (2.498, 2.517, 2.542), stdev = 0.023
  CI (99.9%): [2.104, 2.930] (assumes normal distribution)


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
# Warmup Iteration   1: 3.835 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.437 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.436 ±(99.9%) 0.004 ms/op
Iteration   1: 2.414 ±(99.9%) 0.003 ms/op
Iteration   2: 2.439 ±(99.9%) 0.004 ms/op
Iteration   3: 2.417 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.423 ±(99.9%) 0.252 ms/op [Average]
  (min, avg, max) = (2.414, 2.423, 2.439), stdev = 0.014
  CI (99.9%): [2.172, 2.675] (assumes normal distribution)


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
# Warmup Iteration   1: 3.998 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.531 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.496 ±(99.9%) 0.004 ms/op
Iteration   1: 2.492 ±(99.9%) 0.004 ms/op
Iteration   2: 2.474 ±(99.9%) 0.004 ms/op
Iteration   3: 2.477 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.481 ±(99.9%) 0.176 ms/op [Average]
  (min, avg, max) = (2.474, 2.481, 2.492), stdev = 0.010
  CI (99.9%): [2.305, 2.657] (assumes normal distribution)


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
# Warmup Iteration   1: 4.593 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.024 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.991 ±(99.9%) 0.006 ms/op
Iteration   1: 3.007 ±(99.9%) 0.006 ms/op
Iteration   2: 2.998 ±(99.9%) 0.004 ms/op
Iteration   3: 2.980 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.995 ±(99.9%) 0.247 ms/op [Average]
  (min, avg, max) = (2.980, 2.995, 3.007), stdev = 0.014
  CI (99.9%): [2.748, 3.242] (assumes normal distribution)


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
# Warmup Iteration   1: 4.207 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.693 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.517 ±(99.9%) 0.006 ms/op
Iteration   1: 2.505 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.899 ms/op
                 createUser·p0.50:   2.556 ms/op
                 createUser·p0.90:   3.064 ms/op
                 createUser·p0.95:   3.199 ms/op
                 createUser·p0.99:   3.793 ms/op
                 createUser·p0.999:  11.793 ms/op
                 createUser·p0.9999: 14.015 ms/op
                 createUser·p1.00:   14.926 ms/op

Iteration   2: 2.507 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.032 ms/op
                 createUser·p0.50:   2.572 ms/op
                 createUser·p0.90:   3.056 ms/op
                 createUser·p0.95:   3.195 ms/op
                 createUser·p0.99:   3.903 ms/op
                 createUser·p0.999:  9.839 ms/op
                 createUser·p0.9999: 12.259 ms/op
                 createUser·p1.00:   12.435 ms/op

Iteration   3: 2.504 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.976 ms/op
                 createUser·p0.50:   2.572 ms/op
                 createUser·p0.90:   3.047 ms/op
                 createUser·p0.95:   3.178 ms/op
                 createUser·p0.99:   3.744 ms/op
                 createUser·p0.999:  8.600 ms/op
                 createUser·p0.9999: 11.142 ms/op
                 createUser·p1.00:   11.928 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 382811
  mean =      2.505 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 49 
    [ 1.250,  2.500) = 185217 
    [ 2.500,  3.750) = 193362 
    [ 3.750,  5.000) = 3202 
    [ 5.000,  6.250) = 504 
    [ 6.250,  7.500) = 78 
    [ 7.500,  8.750) = 23 
    [ 8.750, 10.000) = 66 
    [10.000, 11.250) = 96 
    [11.250, 12.500) = 106 
    [12.500, 13.750) = 86 
    [13.750, 15.000) = 22 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.899 ms/op
     p(50.0000) =      2.564 ms/op
     p(90.0000) =      3.056 ms/op
     p(95.0000) =      3.191 ms/op
     p(99.0000) =      3.801 ms/op
     p(99.9000) =      8.654 ms/op
     p(99.9900) =     13.512 ms/op
     p(99.9990) =     14.175 ms/op
     p(99.9999) =     14.926 ms/op
    p(100.0000) =     14.926 ms/op


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
# Warmup Iteration   1: 4.009 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.502 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.422 ±(99.9%) 0.005 ms/op
Iteration   1: 2.435 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.104 ms/op
                 existUser·p0.50:   2.535 ms/op
                 existUser·p0.90:   2.957 ms/op
                 existUser·p0.95:   3.064 ms/op
                 existUser·p0.99:   3.547 ms/op
                 existUser·p0.999:  6.705 ms/op
                 existUser·p0.9999: 13.971 ms/op
                 existUser·p1.00:   14.238 ms/op

Iteration   2: 2.441 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.813 ms/op
                 existUser·p0.50:   2.494 ms/op
                 existUser·p0.90:   2.982 ms/op
                 existUser·p0.95:   3.101 ms/op
                 existUser·p0.99:   3.609 ms/op
                 existUser·p0.999:  7.967 ms/op
                 existUser·p0.9999: 14.270 ms/op
                 existUser·p1.00:   16.007 ms/op

Iteration   3: 2.433 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.912 ms/op
                 existUser·p0.50:   2.519 ms/op
                 existUser·p0.90:   2.961 ms/op
                 existUser·p0.95:   3.084 ms/op
                 existUser·p0.99:   3.596 ms/op
                 existUser·p0.999:  7.520 ms/op
                 existUser·p0.9999: 10.215 ms/op
                 existUser·p1.00:   10.781 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 393744
  mean =      2.436 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 34 
    [ 1.250,  2.500) = 195446 
    [ 2.500,  3.750) = 195166 
    [ 3.750,  5.000) = 2311 
    [ 5.000,  6.250) = 361 
    [ 6.250,  7.500) = 29 
    [ 7.500,  8.750) = 44 
    [ 8.750, 10.000) = 105 
    [10.000, 11.250) = 70 
    [11.250, 12.500) = 63 
    [12.500, 13.750) = 81 
    [13.750, 15.000) = 26 
    [15.000, 16.250) = 8 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.813 ms/op
     p(50.0000) =      2.515 ms/op
     p(90.0000) =      2.966 ms/op
     p(95.0000) =      3.084 ms/op
     p(99.0000) =      3.584 ms/op
     p(99.9000) =      7.758 ms/op
     p(99.9900) =     13.675 ms/op
     p(99.9990) =     15.221 ms/op
     p(99.9999) =     16.007 ms/op
    p(100.0000) =     16.007 ms/op


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
# Warmup Iteration   1: 4.071 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.542 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.498 ±(99.9%) 0.006 ms/op
Iteration   1: 2.474 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.895 ms/op
                 getUser·p0.50:   2.494 ms/op
                 getUser·p0.90:   3.027 ms/op
                 getUser·p0.95:   3.170 ms/op
                 getUser·p0.99:   3.953 ms/op
                 getUser·p0.999:  6.692 ms/op
                 getUser·p0.9999: 13.894 ms/op
                 getUser·p1.00:   14.287 ms/op

Iteration   2: 2.526 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.718 ms/op
                 getUser·p0.50:   2.552 ms/op
                 getUser·p0.90:   3.088 ms/op
                 getUser·p0.95:   3.314 ms/op
                 getUser·p0.99:   4.794 ms/op
                 getUser·p0.999:  9.593 ms/op
                 getUser·p0.9999: 14.424 ms/op
                 getUser·p1.00:   15.172 ms/op

Iteration   3: 2.473 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.841 ms/op
                 getUser·p0.50:   2.474 ms/op
                 getUser·p0.90:   3.039 ms/op
                 getUser·p0.95:   3.203 ms/op
                 getUser·p0.99:   3.805 ms/op
                 getUser·p0.999:  6.265 ms/op
                 getUser·p0.9999: 11.422 ms/op
                 getUser·p1.00:   12.337 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 385144
  mean =      2.491 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 88 
    [ 1.250,  2.500) = 192086 
    [ 2.500,  3.750) = 186488 
    [ 3.750,  5.000) = 5025 
    [ 5.000,  6.250) = 1009 
    [ 6.250,  7.500) = 64 
    [ 7.500,  8.750) = 8 
    [ 8.750, 10.000) = 76 
    [10.000, 11.250) = 87 
    [11.250, 12.500) = 79 
    [12.500, 13.750) = 84 
    [13.750, 15.000) = 49 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.718 ms/op
     p(50.0000) =      2.503 ms/op
     p(90.0000) =      3.052 ms/op
     p(95.0000) =      3.224 ms/op
     p(99.0000) =      4.174 ms/op
     p(99.9000) =      7.302 ms/op
     p(99.9900) =     13.894 ms/op
     p(99.9990) =     14.840 ms/op
     p(99.9999) =     15.172 ms/op
    p(100.0000) =     15.172 ms/op


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
# Warmup Iteration   1: 4.872 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 3.054 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.018 ±(99.9%) 0.008 ms/op
Iteration   1: 3.023 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.984 ms/op
                 listUser·p0.50:   2.949 ms/op
                 listUser·p0.90:   3.891 ms/op
                 listUser·p0.95:   4.383 ms/op
                 listUser·p0.99:   5.587 ms/op
                 listUser·p0.999:  10.109 ms/op
                 listUser·p0.9999: 12.063 ms/op
                 listUser·p1.00:   13.156 ms/op

Iteration   2: 3.020 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.652 ms/op
                 listUser·p0.50:   2.937 ms/op
                 listUser·p0.90:   3.916 ms/op
                 listUser·p0.95:   4.456 ms/op
                 listUser·p0.99:   5.734 ms/op
                 listUser·p0.999:  9.781 ms/op
                 listUser·p0.9999: 11.689 ms/op
                 listUser·p1.00:   12.861 ms/op

Iteration   3: 2.997 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.982 ms/op
                 listUser·p0.50:   2.933 ms/op
                 listUser·p0.90:   3.842 ms/op
                 listUser·p0.95:   4.309 ms/op
                 listUser·p0.99:   5.530 ms/op
                 listUser·p0.999:  9.912 ms/op
                 listUser·p0.9999: 13.964 ms/op
                 listUser·p1.00:   14.598 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 318290
  mean =      3.013 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 105 
    [ 1.250,  2.500) = 90925 
    [ 2.500,  3.750) = 187832 
    [ 3.750,  5.000) = 31922 
    [ 5.000,  6.250) = 6049 
    [ 6.250,  7.500) = 743 
    [ 7.500,  8.750) = 185 
    [ 8.750, 10.000) = 233 
    [10.000, 11.250) = 167 
    [11.250, 12.500) = 74 
    [12.500, 13.750) = 40 
    [13.750, 15.000) = 15 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.652 ms/op
     p(50.0000) =      2.941 ms/op
     p(90.0000) =      3.883 ms/op
     p(95.0000) =      4.383 ms/op
     p(99.0000) =      5.620 ms/op
     p(99.9000) =      9.912 ms/op
     p(99.9900) =     12.867 ms/op
     p(99.9990) =     14.464 ms/op
     p(99.9999) =     14.598 ms/op
    p(100.0000) =     14.598 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.680 ± 1.217  ops/ms
ClientPb.existUser                       thrpt       3  13.077 ± 1.652  ops/ms
ClientPb.getUser                         thrpt       3  12.710 ± 1.500  ops/ms
ClientPb.listUser                        thrpt       3  10.755 ± 0.599  ops/ms
ClientPb.createUser                       avgt       3   2.517 ± 0.413   ms/op
ClientPb.existUser                        avgt       3   2.423 ± 0.252   ms/op
ClientPb.getUser                          avgt       3   2.481 ± 0.176   ms/op
ClientPb.listUser                         avgt       3   2.995 ± 0.247   ms/op
ClientPb.createUser                     sample  382811   2.505 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.899           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.564           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.056           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.191           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.801           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.654           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.512           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.926           ms/op
ClientPb.existUser                      sample  393744   2.436 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.813           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.515           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.966           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.084           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.584           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.758           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.675           ms/op
ClientPb.existUser:existUser·p1.00      sample          16.007           ms/op
ClientPb.getUser                        sample  385144   2.491 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.718           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.503           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.052           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.224           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.174           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.302           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.894           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.172           ms/op
ClientPb.listUser                       sample  318290   3.013 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.652           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.941           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.883           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.383           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.620           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.912           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.867           ms/op
ClientPb.listUser:listUser·p1.00        sample          14.598           ms/op
