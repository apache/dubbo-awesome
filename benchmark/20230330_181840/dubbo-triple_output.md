# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.384 ops/ms
# Warmup Iteration   2: 5.376 ops/ms
# Warmup Iteration   3: 9.251 ops/ms
Iteration   1: 9.456 ops/ms
Iteration   2: 9.590 ops/ms
Iteration   3: 9.592 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.546 ±(99.9%) 1.419 ops/ms [Average]
  (min, avg, max) = (9.456, 9.546, 9.592), stdev = 0.078
  CI (99.9%): [8.127, 10.966] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.785 ops/ms
# Warmup Iteration   2: 8.793 ops/ms
# Warmup Iteration   3: 10.087 ops/ms
Iteration   1: 10.303 ops/ms
Iteration   2: 10.510 ops/ms
Iteration   3: 10.694 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.503 ±(99.9%) 3.571 ops/ms [Average]
  (min, avg, max) = (10.303, 10.503, 10.694), stdev = 0.196
  CI (99.9%): [6.932, 14.074] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.574 ops/ms
# Warmup Iteration   2: 9.090 ops/ms
# Warmup Iteration   3: 9.851 ops/ms
Iteration   1: 9.745 ops/ms
Iteration   2: 9.820 ops/ms
Iteration   3: 9.810 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.792 ±(99.9%) 0.738 ops/ms [Average]
  (min, avg, max) = (9.745, 9.792, 9.820), stdev = 0.040
  CI (99.9%): [9.053, 10.530] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.399 ops/ms
# Warmup Iteration   2: 7.862 ops/ms
# Warmup Iteration   3: 8.232 ops/ms
Iteration   1: 8.434 ops/ms
Iteration   2: 8.402 ops/ms
Iteration   3: 8.266 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.368 ±(99.9%) 1.627 ops/ms [Average]
  (min, avg, max) = (8.266, 8.368, 8.434), stdev = 0.089
  CI (99.9%): [6.740, 9.995] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 7.531 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.503 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.275 ±(99.9%) 0.007 ms/op
Iteration   1: 3.147 ±(99.9%) 0.005 ms/op
Iteration   2: 3.176 ±(99.9%) 0.003 ms/op
Iteration   3: 3.098 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.140 ±(99.9%) 0.713 ms/op [Average]
  (min, avg, max) = (3.098, 3.140, 3.176), stdev = 0.039
  CI (99.9%): [2.427, 3.854] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 7.879 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.295 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.185 ±(99.9%) 0.003 ms/op
Iteration   1: 3.019 ±(99.9%) 0.004 ms/op
Iteration   2: 3.112 ±(99.9%) 0.003 ms/op
Iteration   3: 3.051 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.061 ±(99.9%) 0.861 ms/op [Average]
  (min, avg, max) = (3.019, 3.061, 3.112), stdev = 0.047
  CI (99.9%): [2.200, 3.921] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 8.121 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.603 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.402 ±(99.9%) 0.004 ms/op
Iteration   1: 3.205 ±(99.9%) 0.005 ms/op
Iteration   2: 3.148 ±(99.9%) 0.004 ms/op
Iteration   3: 3.171 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.175 ±(99.9%) 0.524 ms/op [Average]
  (min, avg, max) = (3.148, 3.175, 3.205), stdev = 0.029
  CI (99.9%): [2.650, 3.699] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 9.130 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 4.103 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.753 ±(99.9%) 0.007 ms/op
Iteration   1: 3.719 ±(99.9%) 0.011 ms/op
Iteration   2: 3.679 ±(99.9%) 0.015 ms/op
Iteration   3: 3.728 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.709 ±(99.9%) 0.478 ms/op [Average]
  (min, avg, max) = (3.679, 3.709, 3.728), stdev = 0.026
  CI (99.9%): [3.231, 4.186] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 7.712 ±(99.9%) 0.092 ms/op
# Warmup Iteration   2: 3.624 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.177 ±(99.9%) 0.008 ms/op
Iteration   1: 3.233 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.563 ms/op
                 createUser·p0.50:   3.084 ms/op
                 createUser·p0.90:   3.711 ms/op
                 createUser·p0.95:   3.957 ms/op
                 createUser·p0.99:   5.571 ms/op
                 createUser·p0.999:  19.019 ms/op
                 createUser·p0.9999: 26.026 ms/op
                 createUser·p1.00:   27.591 ms/op

Iteration   2: 3.116 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.446 ms/op
                 createUser·p0.50:   3.068 ms/op
                 createUser·p0.90:   3.322 ms/op
                 createUser·p0.95:   3.629 ms/op
                 createUser·p0.99:   5.209 ms/op
                 createUser·p0.999:  10.068 ms/op
                 createUser·p0.9999: 21.586 ms/op
                 createUser·p1.00:   22.479 ms/op

Iteration   3: 3.235 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.606 ms/op
                 createUser·p0.50:   3.105 ms/op
                 createUser·p0.90:   3.699 ms/op
                 createUser·p0.95:   3.985 ms/op
                 createUser·p0.99:   5.505 ms/op
                 createUser·p0.999:  16.089 ms/op
                 createUser·p0.9999: 19.698 ms/op
                 createUser·p1.00:   20.513 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 300070
  mean =      3.194 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11368 
    [ 2.500,  5.000) = 283438 
    [ 5.000,  7.500) = 4468 
    [ 7.500, 10.000) = 370 
    [10.000, 12.500) = 55 
    [12.500, 15.000) = 18 
    [15.000, 17.500) = 84 
    [17.500, 20.000) = 149 
    [20.000, 22.500) = 57 
    [22.500, 25.000) = 38 
    [25.000, 27.500) = 24 

  Percentiles, ms/op:
      p(0.0000) =      1.446 ms/op
     p(50.0000) =      3.084 ms/op
     p(90.0000) =      3.617 ms/op
     p(95.0000) =      3.916 ms/op
     p(99.0000) =      5.480 ms/op
     p(99.9000) =     16.971 ms/op
     p(99.9900) =     24.805 ms/op
     p(99.9990) =     27.165 ms/op
     p(99.9999) =     27.591 ms/op
    p(100.0000) =     27.591 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 7.136 ±(99.9%) 0.093 ms/op
# Warmup Iteration   2: 3.316 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.094 ±(99.9%) 0.007 ms/op
Iteration   1: 3.096 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.335 ms/op
                 existUser·p0.50:   3.068 ms/op
                 existUser·p0.90:   3.363 ms/op
                 existUser·p0.95:   3.690 ms/op
                 existUser·p0.99:   5.218 ms/op
                 existUser·p0.999:  9.537 ms/op
                 existUser·p0.9999: 19.781 ms/op
                 existUser·p1.00:   20.972 ms/op

Iteration   2: 3.094 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.497 ms/op
                 existUser·p0.50:   3.088 ms/op
                 existUser·p0.90:   3.277 ms/op
                 existUser·p0.95:   3.584 ms/op
                 existUser·p0.99:   5.375 ms/op
                 existUser·p0.999:  9.943 ms/op
                 existUser·p0.9999: 22.096 ms/op
                 existUser·p1.00:   23.101 ms/op

Iteration   3: 3.103 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.438 ms/op
                 existUser·p0.50:   3.084 ms/op
                 existUser·p0.90:   3.359 ms/op
                 existUser·p0.95:   3.604 ms/op
                 existUser·p0.99:   5.395 ms/op
                 existUser·p0.999:  14.074 ms/op
                 existUser·p0.9999: 21.299 ms/op
                 existUser·p1.00:   21.856 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 309879
  mean =      3.098 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 26768 
    [ 2.500,  5.000) = 277602 
    [ 5.000,  7.500) = 4794 
    [ 7.500, 10.000) = 331 
    [10.000, 12.500) = 81 
    [12.500, 15.000) = 36 
    [15.000, 17.500) = 50 
    [17.500, 20.000) = 119 
    [20.000, 22.500) = 95 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.335 ms/op
     p(50.0000) =      3.080 ms/op
     p(90.0000) =      3.338 ms/op
     p(95.0000) =      3.633 ms/op
     p(99.0000) =      5.333 ms/op
     p(99.9000) =     11.289 ms/op
     p(99.9900) =     21.660 ms/op
     p(99.9990) =     22.508 ms/op
     p(99.9999) =     23.101 ms/op
    p(100.0000) =     23.101 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 8.006 ±(99.9%) 0.101 ms/op
# Warmup Iteration   2: 3.451 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.319 ±(99.9%) 0.011 ms/op
Iteration   1: 3.338 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.017 ms/op
                 getUser·p0.50:   3.170 ms/op
                 getUser·p0.90:   3.887 ms/op
                 getUser·p0.95:   4.424 ms/op
                 getUser·p0.99:   6.431 ms/op
                 getUser·p0.999:  15.190 ms/op
                 getUser·p0.9999: 19.379 ms/op
                 getUser·p1.00:   19.923 ms/op

Iteration   2: 3.230 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.079 ms/op
                 getUser·p0.50:   3.174 ms/op
                 getUser·p0.90:   3.568 ms/op
                 getUser·p0.95:   3.768 ms/op
                 getUser·p0.99:   5.603 ms/op
                 getUser·p0.999:  16.259 ms/op
                 getUser·p0.9999: 22.348 ms/op
                 getUser·p1.00:   22.577 ms/op

Iteration   3: 3.226 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.444 ms/op
                 getUser·p0.50:   3.092 ms/op
                 getUser·p0.90:   3.662 ms/op
                 getUser·p0.95:   4.415 ms/op
                 getUser·p0.99:   5.489 ms/op
                 getUser·p0.999:  14.891 ms/op
                 getUser·p0.9999: 20.721 ms/op
                 getUser·p1.00:   25.887 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 294141
  mean =      3.264 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11764 
    [ 2.500,  5.000) = 274777 
    [ 5.000,  7.500) = 6689 
    [ 7.500, 10.000) = 389 
    [10.000, 12.500) = 171 
    [12.500, 15.000) = 67 
    [15.000, 17.500) = 79 
    [17.500, 20.000) = 136 
    [20.000, 22.500) = 63 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      1.017 ms/op
     p(50.0000) =      3.146 ms/op
     p(90.0000) =      3.674 ms/op
     p(95.0000) =      4.309 ms/op
     p(99.0000) =      5.898 ms/op
     p(99.9000) =     14.891 ms/op
     p(99.9900) =     21.318 ms/op
     p(99.9990) =     25.887 ms/op
     p(99.9999) =     25.887 ms/op
    p(100.0000) =     25.887 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 9.802 ±(99.9%) 0.117 ms/op
# Warmup Iteration   2: 4.215 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.784 ±(99.9%) 0.011 ms/op
Iteration   1: 3.792 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.845 ms/op
                 listUser·p0.50:   3.723 ms/op
                 listUser·p0.90:   4.092 ms/op
                 listUser·p0.95:   4.456 ms/op
                 listUser·p0.99:   6.783 ms/op
                 listUser·p0.999:  16.466 ms/op
                 listUser·p0.9999: 21.318 ms/op
                 listUser·p1.00:   22.348 ms/op

Iteration   2: 3.755 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.138 ms/op
                 listUser·p0.50:   3.699 ms/op
                 listUser·p0.90:   4.112 ms/op
                 listUser·p0.95:   4.383 ms/op
                 listUser·p0.99:   6.799 ms/op
                 listUser·p0.999:  12.399 ms/op
                 listUser·p0.9999: 14.229 ms/op
                 listUser·p1.00:   14.516 ms/op

Iteration   3: 3.827 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.042 ms/op
                 listUser·p0.50:   3.695 ms/op
                 listUser·p0.90:   4.358 ms/op
                 listUser·p0.95:   4.637 ms/op
                 listUser·p0.99:   7.086 ms/op
                 listUser·p0.999:  14.277 ms/op
                 listUser·p0.9999: 16.049 ms/op
                 listUser·p1.00:   16.777 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 253130
  mean =      3.791 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 51 
    [ 2.500,  5.000) = 245793 
    [ 5.000,  7.500) = 5626 
    [ 7.500, 10.000) = 933 
    [10.000, 12.500) = 268 
    [12.500, 15.000) = 271 
    [15.000, 17.500) = 153 
    [17.500, 20.000) = 15 
    [20.000, 22.500) = 20 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.845 ms/op
     p(50.0000) =      3.703 ms/op
     p(90.0000) =      4.202 ms/op
     p(95.0000) =      4.517 ms/op
     p(99.0000) =      6.865 ms/op
     p(99.9000) =     14.236 ms/op
     p(99.9900) =     19.235 ms/op
     p(99.9990) =     22.099 ms/op
     p(99.9999) =     22.348 ms/op
    p(100.0000) =     22.348 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.546 ± 1.419  ops/ms
ClientPb.existUser                       thrpt       3  10.503 ± 3.571  ops/ms
ClientPb.getUser                         thrpt       3   9.792 ± 0.738  ops/ms
ClientPb.listUser                        thrpt       3   8.368 ± 1.627  ops/ms
ClientPb.createUser                       avgt       3   3.140 ± 0.713   ms/op
ClientPb.existUser                        avgt       3   3.061 ± 0.861   ms/op
ClientPb.getUser                          avgt       3   3.175 ± 0.524   ms/op
ClientPb.listUser                         avgt       3   3.709 ± 0.478   ms/op
ClientPb.createUser                     sample  300070   3.194 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.446           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.084           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.617           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.916           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.480           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.971           ms/op
ClientPb.createUser:createUser·p0.9999  sample          24.805           ms/op
ClientPb.createUser:createUser·p1.00    sample          27.591           ms/op
ClientPb.existUser                      sample  309879   3.098 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.335           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.080           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.338           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.633           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.333           ms/op
ClientPb.existUser:existUser·p0.999     sample          11.289           ms/op
ClientPb.existUser:existUser·p0.9999    sample          21.660           ms/op
ClientPb.existUser:existUser·p1.00      sample          23.101           ms/op
ClientPb.getUser                        sample  294141   3.264 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.017           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.146           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.674           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.309           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.898           ms/op
ClientPb.getUser:getUser·p0.999         sample          14.891           ms/op
ClientPb.getUser:getUser·p0.9999        sample          21.318           ms/op
ClientPb.getUser:getUser·p1.00          sample          25.887           ms/op
ClientPb.listUser                       sample  253130   3.791 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.845           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.703           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.202           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.517           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.865           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.236           ms/op
ClientPb.listUser:listUser·p0.9999      sample          19.235           ms/op
ClientPb.listUser:listUser·p1.00        sample          22.348           ms/op
