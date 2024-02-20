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
# Warmup Iteration   1: 4.255 ops/ms
# Warmup Iteration   2: 11.847 ops/ms
# Warmup Iteration   3: 12.182 ops/ms
Iteration   1: 12.495 ops/ms
Iteration   2: 12.598 ops/ms
Iteration   3: 12.656 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.583 ±(99.9%) 1.489 ops/ms [Average]
  (min, avg, max) = (12.495, 12.583, 12.656), stdev = 0.082
  CI (99.9%): [11.094, 14.072] (assumes normal distribution)


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
# Warmup Iteration   1: 8.450 ops/ms
# Warmup Iteration   2: 12.785 ops/ms
# Warmup Iteration   3: 12.961 ops/ms
Iteration   1: 12.816 ops/ms
Iteration   2: 13.110 ops/ms
Iteration   3: 13.040 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.988 ±(99.9%) 2.800 ops/ms [Average]
  (min, avg, max) = (12.816, 12.988, 13.110), stdev = 0.153
  CI (99.9%): [10.188, 15.788] (assumes normal distribution)


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
# Warmup Iteration   1: 7.823 ops/ms
# Warmup Iteration   2: 12.529 ops/ms
# Warmup Iteration   3: 12.656 ops/ms
Iteration   1: 12.691 ops/ms
Iteration   2: 12.675 ops/ms
Iteration   3: 12.566 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.644 ±(99.9%) 1.245 ops/ms [Average]
  (min, avg, max) = (12.566, 12.644, 12.691), stdev = 0.068
  CI (99.9%): [11.399, 13.889] (assumes normal distribution)


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
# Warmup Iteration   1: 6.734 ops/ms
# Warmup Iteration   2: 10.441 ops/ms
# Warmup Iteration   3: 10.436 ops/ms
Iteration   1: 10.613 ops/ms
Iteration   2: 10.599 ops/ms
Iteration   3: 10.647 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.620 ±(99.9%) 0.451 ops/ms [Average]
  (min, avg, max) = (10.599, 10.620, 10.647), stdev = 0.025
  CI (99.9%): [10.168, 11.071] (assumes normal distribution)


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
# Warmup Iteration   1: 4.095 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.668 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.567 ±(99.9%) 0.004 ms/op
Iteration   1: 2.566 ±(99.9%) 0.004 ms/op
Iteration   2: 2.565 ±(99.9%) 0.005 ms/op
Iteration   3: 2.543 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.558 ±(99.9%) 0.241 ms/op [Average]
  (min, avg, max) = (2.543, 2.558, 2.566), stdev = 0.013
  CI (99.9%): [2.317, 2.799] (assumes normal distribution)


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
# Warmup Iteration   1: 3.589 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.488 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.468 ±(99.9%) 0.003 ms/op
Iteration   1: 2.464 ±(99.9%) 0.004 ms/op
Iteration   2: 2.486 ±(99.9%) 0.005 ms/op
Iteration   3: 2.493 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.481 ±(99.9%) 0.271 ms/op [Average]
  (min, avg, max) = (2.464, 2.481, 2.493), stdev = 0.015
  CI (99.9%): [2.210, 2.752] (assumes normal distribution)


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
# Warmup Iteration   1: 3.871 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.531 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.518 ±(99.9%) 0.004 ms/op
Iteration   1: 2.504 ±(99.9%) 0.004 ms/op
Iteration   2: 2.501 ±(99.9%) 0.005 ms/op
Iteration   3: 2.496 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.500 ±(99.9%) 0.074 ms/op [Average]
  (min, avg, max) = (2.496, 2.500, 2.504), stdev = 0.004
  CI (99.9%): [2.427, 2.574] (assumes normal distribution)


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
# Warmup Iteration   1: 4.762 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.101 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.053 ±(99.9%) 0.005 ms/op
Iteration   1: 3.057 ±(99.9%) 0.004 ms/op
Iteration   2: 3.046 ±(99.9%) 0.006 ms/op
Iteration   3: 3.051 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.051 ±(99.9%) 0.100 ms/op [Average]
  (min, avg, max) = (3.046, 3.051, 3.057), stdev = 0.005
  CI (99.9%): [2.952, 3.151] (assumes normal distribution)


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
# Warmup Iteration   1: 4.311 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 2.656 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.574 ±(99.9%) 0.006 ms/op
Iteration   1: 2.589 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.038 ms/op
                 createUser·p0.50:   2.621 ms/op
                 createUser·p0.90:   3.158 ms/op
                 createUser·p0.95:   3.285 ms/op
                 createUser·p0.99:   3.834 ms/op
                 createUser·p0.999:  11.887 ms/op
                 createUser·p0.9999: 14.199 ms/op
                 createUser·p1.00:   14.729 ms/op

Iteration   2: 2.566 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.851 ms/op
                 createUser·p0.50:   2.634 ms/op
                 createUser·p0.90:   3.117 ms/op
                 createUser·p0.95:   3.244 ms/op
                 createUser·p0.99:   3.985 ms/op
                 createUser·p0.999:  9.485 ms/op
                 createUser·p0.9999: 13.609 ms/op
                 createUser·p1.00:   14.860 ms/op

Iteration   3: 2.573 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.882 ms/op
                 createUser·p0.50:   2.613 ms/op
                 createUser·p0.90:   3.138 ms/op
                 createUser·p0.95:   3.273 ms/op
                 createUser·p0.99:   3.936 ms/op
                 createUser·p0.999:  8.462 ms/op
                 createUser·p0.9999: 11.619 ms/op
                 createUser·p1.00:   12.435 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 372281
  mean =      2.576 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 46 
    [ 1.250,  2.500) = 175645 
    [ 2.500,  3.750) = 191528 
    [ 3.750,  5.000) = 4218 
    [ 5.000,  6.250) = 435 
    [ 6.250,  7.500) = 25 
    [ 7.500,  8.750) = 18 
    [ 8.750, 10.000) = 69 
    [10.000, 11.250) = 56 
    [11.250, 12.500) = 111 
    [12.500, 13.750) = 102 
    [13.750, 15.000) = 28 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.851 ms/op
     p(50.0000) =      2.621 ms/op
     p(90.0000) =      3.138 ms/op
     p(95.0000) =      3.269 ms/op
     p(99.0000) =      3.912 ms/op
     p(99.9000) =      8.602 ms/op
     p(99.9900) =     13.575 ms/op
     p(99.9990) =     14.844 ms/op
     p(99.9999) =     14.860 ms/op
    p(100.0000) =     14.860 ms/op


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
# Warmup Iteration   1: 3.729 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.520 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.479 ±(99.9%) 0.005 ms/op
Iteration   1: 2.476 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.822 ms/op
                 existUser·p0.50:   2.515 ms/op
                 existUser·p0.90:   3.015 ms/op
                 existUser·p0.95:   3.117 ms/op
                 existUser·p0.99:   3.523 ms/op
                 existUser·p0.999:  5.813 ms/op
                 existUser·p0.9999: 13.634 ms/op
                 existUser·p1.00:   14.221 ms/op

Iteration   2: 2.487 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.762 ms/op
                 existUser·p0.50:   2.523 ms/op
                 existUser·p0.90:   3.035 ms/op
                 existUser·p0.95:   3.150 ms/op
                 existUser·p0.99:   3.690 ms/op
                 existUser·p0.999:  6.364 ms/op
                 existUser·p0.9999: 13.082 ms/op
                 existUser·p1.00:   13.566 ms/op

Iteration   3: 2.529 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.953 ms/op
                 existUser·p0.50:   2.564 ms/op
                 existUser·p0.90:   3.080 ms/op
                 existUser·p0.95:   3.215 ms/op
                 existUser·p0.99:   4.043 ms/op
                 existUser·p0.999:  8.357 ms/op
                 existUser·p0.9999: 18.505 ms/op
                 existUser·p1.00:   19.137 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 384067
  mean =      2.497 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 52 
    [ 1.250,  2.500) = 189378 
    [ 2.500,  3.750) = 190929 
    [ 3.750,  5.000) = 2845 
    [ 5.000,  6.250) = 461 
    [ 6.250,  7.500) = 33 
    [ 7.500,  8.750) = 22 
    [ 8.750, 10.000) = 67 
    [10.000, 11.250) = 86 
    [11.250, 12.500) = 71 
    [12.500, 13.750) = 83 
    [13.750, 15.000) = 8 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 26 

  Percentiles, ms/op:
      p(0.0000) =      0.762 ms/op
     p(50.0000) =      2.531 ms/op
     p(90.0000) =      3.043 ms/op
     p(95.0000) =      3.158 ms/op
     p(99.0000) =      3.731 ms/op
     p(99.9000) =      7.207 ms/op
     p(99.9900) =     13.815 ms/op
     p(99.9990) =     19.038 ms/op
     p(99.9999) =     19.137 ms/op
    p(100.0000) =     19.137 ms/op


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
# Warmup Iteration   1: 3.985 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.608 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.532 ±(99.9%) 0.006 ms/op
Iteration   1: 2.519 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.974 ms/op
                 getUser·p0.50:   2.548 ms/op
                 getUser·p0.90:   3.072 ms/op
                 getUser·p0.95:   3.211 ms/op
                 getUser·p0.99:   3.924 ms/op
                 getUser·p0.999:  11.767 ms/op
                 getUser·p0.9999: 20.641 ms/op
                 getUser·p1.00:   22.249 ms/op

Iteration   2: 2.532 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.991 ms/op
                 getUser·p0.50:   2.548 ms/op
                 getUser·p0.90:   3.084 ms/op
                 getUser·p0.95:   3.224 ms/op
                 getUser·p0.99:   3.962 ms/op
                 getUser·p0.999:  9.814 ms/op
                 getUser·p0.9999: 13.439 ms/op
                 getUser·p1.00:   14.385 ms/op

Iteration   3: 2.525 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.013 ms/op
                 getUser·p0.50:   2.519 ms/op
                 getUser·p0.90:   3.097 ms/op
                 getUser·p0.95:   3.248 ms/op
                 getUser·p0.99:   3.961 ms/op
                 getUser·p0.999:  8.105 ms/op
                 getUser·p0.9999: 11.370 ms/op
                 getUser·p1.00:   11.616 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 379819
  mean =      2.525 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 186399 
    [ 2.500,  5.000) = 192200 
    [ 5.000,  7.500) = 834 
    [ 7.500, 10.000) = 76 
    [10.000, 12.500) = 173 
    [12.500, 15.000) = 105 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 6 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.974 ms/op
     p(50.0000) =      2.535 ms/op
     p(90.0000) =      3.084 ms/op
     p(95.0000) =      3.228 ms/op
     p(99.0000) =      3.949 ms/op
     p(99.9000) =      8.143 ms/op
     p(99.9900) =     14.254 ms/op
     p(99.9990) =     22.099 ms/op
     p(99.9999) =     22.249 ms/op
    p(100.0000) =     22.249 ms/op


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
# Warmup Iteration   1: 4.613 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 3.099 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.067 ±(99.9%) 0.009 ms/op
Iteration   1: 3.053 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.824 ms/op
                 listUser·p0.50:   2.998 ms/op
                 listUser·p0.90:   3.949 ms/op
                 listUser·p0.95:   4.399 ms/op
                 listUser·p0.99:   5.546 ms/op
                 listUser·p0.999:  9.142 ms/op
                 listUser·p0.9999: 11.985 ms/op
                 listUser·p1.00:   12.403 ms/op

Iteration   2: 3.042 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.701 ms/op
                 listUser·p0.50:   2.982 ms/op
                 listUser·p0.90:   3.903 ms/op
                 listUser·p0.95:   4.358 ms/op
                 listUser·p0.99:   5.513 ms/op
                 listUser·p0.999:  10.026 ms/op
                 listUser·p0.9999: 11.993 ms/op
                 listUser·p1.00:   12.370 ms/op

Iteration   3: 3.043 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.944 ms/op
                 listUser·p0.50:   2.982 ms/op
                 listUser·p0.90:   3.899 ms/op
                 listUser·p0.95:   4.391 ms/op
                 listUser·p0.99:   5.521 ms/op
                 listUser·p0.999:  9.714 ms/op
                 listUser·p0.9999: 12.960 ms/op
                 listUser·p1.00:   13.828 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 314871
  mean =      3.046 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 93 
    [ 1.250,  2.500) = 82766 
    [ 2.500,  3.750) = 190877 
    [ 3.750,  5.000) = 34136 
    [ 5.000,  6.250) = 5816 
    [ 6.250,  7.500) = 532 
    [ 7.500,  8.750) = 205 
    [ 8.750, 10.000) = 180 
    [10.000, 11.250) = 191 
    [11.250, 12.500) = 57 
    [12.500, 13.750) = 17 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.701 ms/op
     p(50.0000) =      2.986 ms/op
     p(90.0000) =      3.916 ms/op
     p(95.0000) =      4.383 ms/op
     p(99.0000) =      5.530 ms/op
     p(99.9000) =      9.667 ms/op
     p(99.9900) =     12.214 ms/op
     p(99.9990) =     13.471 ms/op
     p(99.9999) =     13.828 ms/op
    p(100.0000) =     13.828 ms/op


# Run complete. Total time: 00:12:57

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.583 ± 1.489  ops/ms
ClientPb.existUser                       thrpt       3  12.988 ± 2.800  ops/ms
ClientPb.getUser                         thrpt       3  12.644 ± 1.245  ops/ms
ClientPb.listUser                        thrpt       3  10.620 ± 0.451  ops/ms
ClientPb.createUser                       avgt       3   2.558 ± 0.241   ms/op
ClientPb.existUser                        avgt       3   2.481 ± 0.271   ms/op
ClientPb.getUser                          avgt       3   2.500 ± 0.074   ms/op
ClientPb.listUser                         avgt       3   3.051 ± 0.100   ms/op
ClientPb.createUser                     sample  372281   2.576 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.851           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.621           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.138           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.269           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.912           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.602           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.575           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.860           ms/op
ClientPb.existUser                      sample  384067   2.497 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.762           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.531           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.043           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.158           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.731           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.207           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.815           ms/op
ClientPb.existUser:existUser·p1.00      sample          19.137           ms/op
ClientPb.getUser                        sample  379819   2.525 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.974           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.535           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.084           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.228           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.949           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.143           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.254           ms/op
ClientPb.getUser:getUser·p1.00          sample          22.249           ms/op
ClientPb.listUser                       sample  314871   3.046 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.701           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.986           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.916           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.383           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.530           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.667           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.214           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.828           ms/op
