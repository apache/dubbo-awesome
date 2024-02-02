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
# Warmup Iteration   1: 4.788 ops/ms
# Warmup Iteration   2: 11.950 ops/ms
# Warmup Iteration   3: 12.192 ops/ms
Iteration   1: 12.510 ops/ms
Iteration   2: 12.443 ops/ms
Iteration   3: 12.513 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.489 ±(99.9%) 0.717 ops/ms [Average]
  (min, avg, max) = (12.443, 12.489, 12.513), stdev = 0.039
  CI (99.9%): [11.772, 13.206] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:52
# Fork: 1 of 1
# Warmup Iteration   1: 8.187 ops/ms
# Warmup Iteration   2: 13.029 ops/ms
# Warmup Iteration   3: 12.973 ops/ms
Iteration   1: 12.841 ops/ms
Iteration   2: 12.945 ops/ms
Iteration   3: 13.076 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.954 ±(99.9%) 2.149 ops/ms [Average]
  (min, avg, max) = (12.841, 12.954, 13.076), stdev = 0.118
  CI (99.9%): [10.804, 15.103] (assumes normal distribution)


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
# Warmup Iteration   1: 8.150 ops/ms
# Warmup Iteration   2: 12.557 ops/ms
# Warmup Iteration   3: 12.798 ops/ms
Iteration   1: 12.679 ops/ms
Iteration   2: 12.820 ops/ms
Iteration   3: 12.579 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.693 ±(99.9%) 2.214 ops/ms [Average]
  (min, avg, max) = (12.579, 12.693, 12.820), stdev = 0.121
  CI (99.9%): [10.479, 14.907] (assumes normal distribution)


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
# Warmup Iteration   1: 6.686 ops/ms
# Warmup Iteration   2: 10.450 ops/ms
# Warmup Iteration   3: 10.537 ops/ms
Iteration   1: 10.504 ops/ms
Iteration   2: 10.575 ops/ms
Iteration   3: 10.585 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.555 ±(99.9%) 0.801 ops/ms [Average]
  (min, avg, max) = (10.504, 10.555, 10.585), stdev = 0.044
  CI (99.9%): [9.754, 11.356] (assumes normal distribution)


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
# Warmup Iteration   1: 4.046 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.546 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.545 ±(99.9%) 0.004 ms/op
Iteration   1: 2.584 ±(99.9%) 0.006 ms/op
Iteration   2: 2.518 ±(99.9%) 0.004 ms/op
Iteration   3: 2.534 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.545 ±(99.9%) 0.623 ms/op [Average]
  (min, avg, max) = (2.518, 2.545, 2.584), stdev = 0.034
  CI (99.9%): [1.923, 3.168] (assumes normal distribution)


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
# Warmup Iteration   1: 3.840 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.510 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.464 ±(99.9%) 0.004 ms/op
Iteration   1: 2.450 ±(99.9%) 0.003 ms/op
Iteration   2: 2.483 ±(99.9%) 0.004 ms/op
Iteration   3: 2.467 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.467 ±(99.9%) 0.301 ms/op [Average]
  (min, avg, max) = (2.450, 2.467, 2.483), stdev = 0.017
  CI (99.9%): [2.166, 2.768] (assumes normal distribution)


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
# Warmup Iteration   1: 3.937 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.595 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.545 ±(99.9%) 0.005 ms/op
Iteration   1: 2.519 ±(99.9%) 0.004 ms/op
Iteration   2: 2.508 ±(99.9%) 0.005 ms/op
Iteration   3: 2.545 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.524 ±(99.9%) 0.346 ms/op [Average]
  (min, avg, max) = (2.508, 2.524, 2.545), stdev = 0.019
  CI (99.9%): [2.179, 2.870] (assumes normal distribution)


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
# Warmup Iteration   1: 4.822 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.160 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.082 ±(99.9%) 0.006 ms/op
Iteration   1: 3.083 ±(99.9%) 0.005 ms/op
Iteration   2: 3.092 ±(99.9%) 0.005 ms/op
Iteration   3: 3.072 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.082 ±(99.9%) 0.183 ms/op [Average]
  (min, avg, max) = (3.072, 3.082, 3.092), stdev = 0.010
  CI (99.9%): [2.900, 3.265] (assumes normal distribution)


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
# Warmup Iteration   1: 4.283 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 2.686 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.571 ±(99.9%) 0.006 ms/op
Iteration   1: 2.522 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.891 ms/op
                 createUser·p0.50:   2.572 ms/op
                 createUser·p0.90:   3.072 ms/op
                 createUser·p0.95:   3.195 ms/op
                 createUser·p0.99:   3.691 ms/op
                 createUser·p0.999:  11.823 ms/op
                 createUser·p0.9999: 13.768 ms/op
                 createUser·p1.00:   14.303 ms/op

Iteration   2: 2.529 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.916 ms/op
                 createUser·p0.50:   2.609 ms/op
                 createUser·p0.90:   3.072 ms/op
                 createUser·p0.95:   3.191 ms/op
                 createUser·p0.99:   3.731 ms/op
                 createUser·p0.999:  9.266 ms/op
                 createUser·p0.9999: 12.289 ms/op
                 createUser·p1.00:   13.418 ms/op

Iteration   3: 2.564 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.994 ms/op
                 createUser·p0.50:   2.638 ms/op
                 createUser·p0.90:   3.121 ms/op
                 createUser·p0.95:   3.248 ms/op
                 createUser·p0.99:   3.768 ms/op
                 createUser·p0.999:  8.618 ms/op
                 createUser·p0.9999: 13.169 ms/op
                 createUser·p1.00:   15.827 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 377875
  mean =      2.538 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 63 
    [ 1.250,  2.500) = 179794 
    [ 2.500,  3.750) = 194381 
    [ 3.750,  5.000) = 2951 
    [ 5.000,  6.250) = 218 
    [ 6.250,  7.500) = 43 
    [ 7.500,  8.750) = 61 
    [ 8.750, 10.000) = 78 
    [10.000, 11.250) = 88 
    [11.250, 12.500) = 81 
    [12.500, 13.750) = 88 
    [13.750, 15.000) = 26 
    [15.000, 16.250) = 3 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.891 ms/op
     p(50.0000) =      2.605 ms/op
     p(90.0000) =      3.088 ms/op
     p(95.0000) =      3.215 ms/op
     p(99.0000) =      3.731 ms/op
     p(99.9000) =      8.651 ms/op
     p(99.9900) =     13.681 ms/op
     p(99.9990) =     15.047 ms/op
     p(99.9999) =     15.827 ms/op
    p(100.0000) =     15.827 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.599 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 2.439 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.451 ±(99.9%) 0.005 ms/op
Iteration   1: 2.437 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.872 ms/op
                 existUser·p0.50:   2.523 ms/op
                 existUser·p0.90:   2.953 ms/op
                 existUser·p0.95:   3.043 ms/op
                 existUser·p0.99:   3.506 ms/op
                 existUser·p0.999:  5.190 ms/op
                 existUser·p0.9999: 13.753 ms/op
                 existUser·p1.00:   14.533 ms/op

Iteration   2: 2.441 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.000 ms/op
                 existUser·p0.50:   2.531 ms/op
                 existUser·p0.90:   2.953 ms/op
                 existUser·p0.95:   3.039 ms/op
                 existUser·p0.99:   3.535 ms/op
                 existUser·p0.999:  8.324 ms/op
                 existUser·p0.9999: 12.906 ms/op
                 existUser·p1.00:   14.041 ms/op

Iteration   3: 2.459 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.953 ms/op
                 existUser·p0.50:   2.507 ms/op
                 existUser·p0.90:   2.994 ms/op
                 existUser·p0.95:   3.109 ms/op
                 existUser·p0.99:   3.781 ms/op
                 existUser·p0.999:  7.954 ms/op
                 existUser·p0.9999: 12.190 ms/op
                 existUser·p1.00:   13.009 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 392154
  mean =      2.446 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 48 
    [ 1.250,  2.500) = 194604 
    [ 2.500,  3.750) = 194358 
    [ 3.750,  5.000) = 2299 
    [ 5.000,  6.250) = 403 
    [ 6.250,  7.500) = 79 
    [ 7.500,  8.750) = 36 
    [ 8.750, 10.000) = 61 
    [10.000, 11.250) = 119 
    [11.250, 12.500) = 86 
    [12.500, 13.750) = 45 
    [13.750, 15.000) = 16 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.872 ms/op
     p(50.0000) =      2.519 ms/op
     p(90.0000) =      2.966 ms/op
     p(95.0000) =      3.064 ms/op
     p(99.0000) =      3.609 ms/op
     p(99.9000) =      6.659 ms/op
     p(99.9900) =     12.976 ms/op
     p(99.9990) =     14.147 ms/op
     p(99.9999) =     14.533 ms/op
    p(100.0000) =     14.533 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 3.950 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.608 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.555 ±(99.9%) 0.006 ms/op
Iteration   1: 2.565 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.945 ms/op
                 getUser·p0.50:   2.585 ms/op
                 getUser·p0.90:   3.113 ms/op
                 getUser·p0.95:   3.256 ms/op
                 getUser·p0.99:   4.186 ms/op
                 getUser·p0.999:  11.403 ms/op
                 getUser·p0.9999: 13.271 ms/op
                 getUser·p1.00:   13.631 ms/op

Iteration   2: 2.564 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.837 ms/op
                 getUser·p0.50:   2.585 ms/op
                 getUser·p0.90:   3.113 ms/op
                 getUser·p0.95:   3.252 ms/op
                 getUser·p0.99:   4.097 ms/op
                 getUser·p0.999:  9.846 ms/op
                 getUser·p0.9999: 13.341 ms/op
                 getUser·p1.00:   13.861 ms/op

Iteration   3: 2.538 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.956 ms/op
                 getUser·p0.50:   2.585 ms/op
                 getUser·p0.90:   3.084 ms/op
                 getUser·p0.95:   3.199 ms/op
                 getUser·p0.99:   3.875 ms/op
                 getUser·p0.999:  7.930 ms/op
                 getUser·p0.9999: 11.128 ms/op
                 getUser·p1.00:   12.108 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 375324
  mean =      2.556 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 43 
    [ 1.250,  2.500) = 182504 
    [ 2.500,  3.750) = 187208 
    [ 3.750,  5.000) = 3902 
    [ 5.000,  6.250) = 1060 
    [ 6.250,  7.500) = 168 
    [ 7.500,  8.750) = 59 
    [ 8.750, 10.000) = 96 
    [10.000, 11.250) = 75 
    [11.250, 12.500) = 116 
    [12.500, 13.750) = 92 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.837 ms/op
     p(50.0000) =      2.585 ms/op
     p(90.0000) =      3.105 ms/op
     p(95.0000) =      3.236 ms/op
     p(99.0000) =      4.030 ms/op
     p(99.9000) =      8.815 ms/op
     p(99.9900) =     12.951 ms/op
     p(99.9990) =     13.672 ms/op
     p(99.9999) =     13.861 ms/op
    p(100.0000) =     13.861 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.569 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 3.114 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.072 ±(99.9%) 0.009 ms/op
Iteration   1: 3.080 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.964 ms/op
                 listUser·p0.50:   3.019 ms/op
                 listUser·p0.90:   3.965 ms/op
                 listUser·p0.95:   4.456 ms/op
                 listUser·p0.99:   5.652 ms/op
                 listUser·p0.999:  9.031 ms/op
                 listUser·p0.9999: 10.463 ms/op
                 listUser·p1.00:   11.272 ms/op

Iteration   2: 3.086 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.966 ms/op
                 listUser·p0.50:   3.023 ms/op
                 listUser·p0.90:   3.998 ms/op
                 listUser·p0.95:   4.489 ms/op
                 listUser·p0.99:   5.652 ms/op
                 listUser·p0.999:  9.100 ms/op
                 listUser·p0.9999: 10.660 ms/op
                 listUser·p1.00:   10.977 ms/op

Iteration   3: 3.115 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.033 ms/op
                 listUser·p0.50:   3.039 ms/op
                 listUser·p0.90:   4.051 ms/op
                 listUser·p0.95:   4.588 ms/op
                 listUser·p0.99:   5.878 ms/op
                 listUser·p0.999:  9.814 ms/op
                 listUser·p0.9999: 13.037 ms/op
                 listUser·p1.00:   14.221 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 310045
  mean =      3.093 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 86 
    [ 1.250,  2.500) = 76901 
    [ 2.500,  3.750) = 188456 
    [ 3.750,  5.000) = 36356 
    [ 5.000,  6.250) = 6668 
    [ 6.250,  7.500) = 869 
    [ 7.500,  8.750) = 273 
    [ 8.750, 10.000) = 291 
    [10.000, 11.250) = 95 
    [11.250, 12.500) = 30 
    [12.500, 13.750) = 16 
    [13.750, 15.000) = 4 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.964 ms/op
     p(50.0000) =      3.027 ms/op
     p(90.0000) =      4.002 ms/op
     p(95.0000) =      4.506 ms/op
     p(99.0000) =      5.734 ms/op
     p(99.9000) =      9.256 ms/op
     p(99.9900) =     11.813 ms/op
     p(99.9990) =     13.859 ms/op
     p(99.9999) =     14.221 ms/op
    p(100.0000) =     14.221 ms/op


# Run complete. Total time: 00:13:00

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.489 ± 0.717  ops/ms
ClientPb.existUser                       thrpt       3  12.954 ± 2.149  ops/ms
ClientPb.getUser                         thrpt       3  12.693 ± 2.214  ops/ms
ClientPb.listUser                        thrpt       3  10.555 ± 0.801  ops/ms
ClientPb.createUser                       avgt       3   2.545 ± 0.623   ms/op
ClientPb.existUser                        avgt       3   2.467 ± 0.301   ms/op
ClientPb.getUser                          avgt       3   2.524 ± 0.346   ms/op
ClientPb.listUser                         avgt       3   3.082 ± 0.183   ms/op
ClientPb.createUser                     sample  377875   2.538 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.891           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.605           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.088           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.215           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.731           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.651           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.681           ms/op
ClientPb.createUser:createUser·p1.00    sample          15.827           ms/op
ClientPb.existUser                      sample  392154   2.446 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.872           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.519           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.966           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.064           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.609           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.659           ms/op
ClientPb.existUser:existUser·p0.9999    sample          12.976           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.533           ms/op
ClientPb.getUser                        sample  375324   2.556 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.837           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.585           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.105           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.236           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.030           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.815           ms/op
ClientPb.getUser:getUser·p0.9999        sample          12.951           ms/op
ClientPb.getUser:getUser·p1.00          sample          13.861           ms/op
ClientPb.listUser                       sample  310045   3.093 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.964           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.027           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.002           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.506           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.734           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.256           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.813           ms/op
ClientPb.listUser:listUser·p1.00        sample          14.221           ms/op
