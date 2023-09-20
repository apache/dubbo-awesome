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
# Warmup Iteration   1: 2.356 ops/ms
# Warmup Iteration   2: 5.388 ops/ms
# Warmup Iteration   3: 8.893 ops/ms
Iteration   1: 9.594 ops/ms
Iteration   2: 9.758 ops/ms
Iteration   3: 9.448 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.600 ±(99.9%) 2.828 ops/ms [Average]
  (min, avg, max) = (9.448, 9.600, 9.758), stdev = 0.155
  CI (99.9%): [6.772, 12.429] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 3.814 ops/ms
# Warmup Iteration   2: 9.118 ops/ms
# Warmup Iteration   3: 9.785 ops/ms
Iteration   1: 10.142 ops/ms
Iteration   2: 10.054 ops/ms
Iteration   3: 10.171 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.123 ±(99.9%) 1.107 ops/ms [Average]
  (min, avg, max) = (10.054, 10.123, 10.171), stdev = 0.061
  CI (99.9%): [9.016, 11.229] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 2.950 ops/ms
# Warmup Iteration   2: 8.852 ops/ms
# Warmup Iteration   3: 9.290 ops/ms
Iteration   1: 9.727 ops/ms
Iteration   2: 9.712 ops/ms
Iteration   3: 9.595 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.678 ±(99.9%) 1.316 ops/ms [Average]
  (min, avg, max) = (9.595, 9.678, 9.727), stdev = 0.072
  CI (99.9%): [8.362, 10.994] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.298 ops/ms
# Warmup Iteration   2: 7.429 ops/ms
# Warmup Iteration   3: 8.217 ops/ms
Iteration   1: 8.000 ops/ms
Iteration   2: 8.234 ops/ms
Iteration   3: 8.242 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.159 ±(99.9%) 2.517 ops/ms [Average]
  (min, avg, max) = (8.000, 8.159, 8.242), stdev = 0.138
  CI (99.9%): [5.642, 10.676] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:49
# Fork: 1 of 1
# Warmup Iteration   1: 9.797 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.582 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.419 ±(99.9%) 0.003 ms/op
Iteration   1: 3.350 ±(99.9%) 0.002 ms/op
Iteration   2: 3.271 ±(99.9%) 0.003 ms/op
Iteration   3: 3.231 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.284 ±(99.9%) 1.104 ms/op [Average]
  (min, avg, max) = (3.231, 3.284, 3.350), stdev = 0.061
  CI (99.9%): [2.180, 4.388] (assumes normal distribution)


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
# Warmup Iteration   1: 7.850 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.365 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.195 ±(99.9%) 0.004 ms/op
Iteration   1: 3.105 ±(99.9%) 0.003 ms/op
Iteration   2: 3.147 ±(99.9%) 0.004 ms/op
Iteration   3: 3.181 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.144 ±(99.9%) 0.694 ms/op [Average]
  (min, avg, max) = (3.105, 3.144, 3.181), stdev = 0.038
  CI (99.9%): [2.450, 3.839] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 9.082 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.487 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.238 ±(99.9%) 0.003 ms/op
Iteration   1: 3.269 ±(99.9%) 0.002 ms/op
Iteration   2: 3.248 ±(99.9%) 0.002 ms/op
Iteration   3: 3.300 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.272 ±(99.9%) 0.481 ms/op [Average]
  (min, avg, max) = (3.248, 3.272, 3.300), stdev = 0.026
  CI (99.9%): [2.791, 3.754] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 9.272 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 4.170 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.957 ±(99.9%) 0.006 ms/op
Iteration   1: 3.819 ±(99.9%) 0.007 ms/op
Iteration   2: 3.917 ±(99.9%) 0.005 ms/op
Iteration   3: 3.781 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.839 ±(99.9%) 1.279 ms/op [Average]
  (min, avg, max) = (3.781, 3.839, 3.917), stdev = 0.070
  CI (99.9%): [2.560, 5.118] (assumes normal distribution)


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
# Warmup Iteration   1: 8.285 ±(99.9%) 0.110 ms/op
# Warmup Iteration   2: 3.657 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.386 ±(99.9%) 0.010 ms/op
Iteration   1: 3.264 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.184 ms/op
                 createUser·p0.50:   3.183 ms/op
                 createUser·p0.90:   3.650 ms/op
                 createUser·p0.95:   3.936 ms/op
                 createUser·p0.99:   5.644 ms/op
                 createUser·p0.999:  15.478 ms/op
                 createUser·p0.9999: 21.549 ms/op
                 createUser·p1.00:   22.282 ms/op

Iteration   2: 3.307 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.307 ms/op
                 createUser·p0.50:   3.187 ms/op
                 createUser·p0.90:   3.744 ms/op
                 createUser·p0.95:   3.994 ms/op
                 createUser·p0.99:   5.603 ms/op
                 createUser·p0.999:  20.346 ms/op
                 createUser·p0.9999: 23.496 ms/op
                 createUser·p1.00:   24.871 ms/op

Iteration   3: 3.397 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.538 ms/op
                 createUser·p0.50:   3.346 ms/op
                 createUser·p0.90:   3.781 ms/op
                 createUser·p0.95:   4.162 ms/op
                 createUser·p0.99:   6.054 ms/op
                 createUser·p0.999:  15.584 ms/op
                 createUser·p0.9999: 18.754 ms/op
                 createUser·p1.00:   20.152 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 288607
  mean =      3.322 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11890 
    [ 2.500,  5.000) = 271587 
    [ 5.000,  7.500) = 3932 
    [ 7.500, 10.000) = 619 
    [10.000, 12.500) = 174 
    [12.500, 15.000) = 67 
    [15.000, 17.500) = 90 
    [17.500, 20.000) = 86 
    [20.000, 22.500) = 128 
    [22.500, 25.000) = 34 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.184 ms/op
     p(50.0000) =      3.252 ms/op
     p(90.0000) =      3.727 ms/op
     p(95.0000) =      4.018 ms/op
     p(99.0000) =      5.718 ms/op
     p(99.9000) =     16.810 ms/op
     p(99.9900) =     22.755 ms/op
     p(99.9990) =     24.402 ms/op
     p(99.9999) =     24.871 ms/op
    p(100.0000) =     24.871 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 7.430 ±(99.9%) 0.093 ms/op
# Warmup Iteration   2: 3.427 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.315 ±(99.9%) 0.009 ms/op
Iteration   1: 3.134 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.991 ms/op
                 existUser·p0.50:   3.076 ms/op
                 existUser·p0.90:   3.396 ms/op
                 existUser·p0.95:   3.650 ms/op
                 existUser·p0.99:   5.628 ms/op
                 existUser·p0.999:  10.843 ms/op
                 existUser·p0.9999: 20.047 ms/op
                 existUser·p1.00:   20.611 ms/op

Iteration   2: 3.138 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.929 ms/op
                 existUser·p0.50:   3.084 ms/op
                 existUser·p0.90:   3.416 ms/op
                 existUser·p0.95:   3.645 ms/op
                 existUser·p0.99:   5.186 ms/op
                 existUser·p0.999:  15.483 ms/op
                 existUser·p0.9999: 25.454 ms/op
                 existUser·p1.00:   25.919 ms/op

Iteration   3: 3.190 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.214 ms/op
                 existUser·p0.50:   3.133 ms/op
                 existUser·p0.90:   3.457 ms/op
                 existUser·p0.95:   3.727 ms/op
                 existUser·p0.99:   5.906 ms/op
                 existUser·p0.999:  10.727 ms/op
                 existUser·p0.9999: 22.969 ms/op
                 existUser·p1.00:   24.609 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 304390
  mean =      3.154 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15851 
    [ 2.500,  5.000) = 283730 
    [ 5.000,  7.500) = 4070 
    [ 7.500, 10.000) = 253 
    [10.000, 12.500) = 194 
    [12.500, 15.000) = 29 
    [15.000, 17.500) = 8 
    [17.500, 20.000) = 141 
    [20.000, 22.500) = 63 
    [22.500, 25.000) = 40 
    [25.000, 27.500) = 11 

  Percentiles, ms/op:
      p(0.0000) =      0.929 ms/op
     p(50.0000) =      3.092 ms/op
     p(90.0000) =      3.424 ms/op
     p(95.0000) =      3.670 ms/op
     p(99.0000) =      5.603 ms/op
     p(99.9000) =     12.183 ms/op
     p(99.9900) =     23.507 ms/op
     p(99.9990) =     25.721 ms/op
     p(99.9999) =     25.919 ms/op
    p(100.0000) =     25.919 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 8.574 ±(99.9%) 0.112 ms/op
# Warmup Iteration   2: 3.706 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.491 ±(99.9%) 0.012 ms/op
Iteration   1: 3.348 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.231 ms/op
                 getUser·p0.50:   3.269 ms/op
                 getUser·p0.90:   3.756 ms/op
                 getUser·p0.95:   4.096 ms/op
                 getUser·p0.99:   6.185 ms/op
                 getUser·p0.999:  17.346 ms/op
                 getUser·p0.9999: 19.759 ms/op
                 getUser·p1.00:   20.447 ms/op

Iteration   2: 3.278 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.198 ms/op
                 getUser·p0.50:   3.199 ms/op
                 getUser·p0.90:   3.641 ms/op
                 getUser·p0.95:   3.924 ms/op
                 getUser·p0.99:   5.956 ms/op
                 getUser·p0.999:  14.709 ms/op
                 getUser·p0.9999: 24.232 ms/op
                 getUser·p1.00:   25.068 ms/op

Iteration   3: 3.397 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.098 ms/op
                 getUser·p0.50:   3.281 ms/op
                 getUser·p0.90:   3.830 ms/op
                 getUser·p0.95:   4.284 ms/op
                 getUser·p0.99:   6.324 ms/op
                 getUser·p0.999:  13.925 ms/op
                 getUser·p0.9999: 23.233 ms/op
                 getUser·p1.00:   23.888 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 287111
  mean =      3.340 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13699 
    [ 2.500,  5.000) = 266844 
    [ 5.000,  7.500) = 5126 
    [ 7.500, 10.000) = 890 
    [10.000, 12.500) = 193 
    [12.500, 15.000) = 64 
    [15.000, 17.500) = 39 
    [17.500, 20.000) = 111 
    [20.000, 22.500) = 64 
    [22.500, 25.000) = 80 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.098 ms/op
     p(50.0000) =      3.248 ms/op
     p(90.0000) =      3.744 ms/op
     p(95.0000) =      4.145 ms/op
     p(99.0000) =      6.136 ms/op
     p(99.9000) =     15.350 ms/op
     p(99.9900) =     23.373 ms/op
     p(99.9990) =     24.728 ms/op
     p(99.9999) =     25.068 ms/op
    p(100.0000) =     25.068 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 10.234 ±(99.9%) 0.130 ms/op
# Warmup Iteration   2: 4.221 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.923 ±(99.9%) 0.013 ms/op
Iteration   1: 4.015 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.067 ms/op
                 listUser·p0.50:   3.805 ms/op
                 listUser·p0.90:   4.415 ms/op
                 listUser·p0.95:   5.235 ms/op
                 listUser·p0.99:   8.092 ms/op
                 listUser·p0.999:  16.810 ms/op
                 listUser·p0.9999: 25.036 ms/op
                 listUser·p1.00:   26.051 ms/op

Iteration   2: 3.804 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.146 ms/op
                 listUser·p0.50:   3.703 ms/op
                 listUser·p0.90:   4.149 ms/op
                 listUser·p0.95:   4.358 ms/op
                 listUser·p0.99:   6.742 ms/op
                 listUser·p0.999:  13.107 ms/op
                 listUser·p0.9999: 16.884 ms/op
                 listUser·p1.00:   17.596 ms/op

Iteration   3: 3.894 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.331 ms/op
                 listUser·p0.50:   3.760 ms/op
                 listUser·p0.90:   4.260 ms/op
                 listUser·p0.95:   4.579 ms/op
                 listUser·p0.99:   7.184 ms/op
                 listUser·p0.999:  14.138 ms/op
                 listUser·p0.9999: 20.185 ms/op
                 listUser·p1.00:   20.480 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 245879
  mean =      3.902 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 100 
    [ 2.500,  5.000) = 236732 
    [ 5.000,  7.500) = 6689 
    [ 7.500, 10.000) = 1622 
    [10.000, 12.500) = 180 
    [12.500, 15.000) = 351 
    [15.000, 17.500) = 113 
    [17.500, 20.000) = 47 
    [20.000, 22.500) = 15 
    [22.500, 25.000) = 21 
    [25.000, 27.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      1.067 ms/op
     p(50.0000) =      3.748 ms/op
     p(90.0000) =      4.276 ms/op
     p(95.0000) =      4.620 ms/op
     p(99.0000) =      7.430 ms/op
     p(99.9000) =     14.189 ms/op
     p(99.9900) =     23.554 ms/op
     p(99.9990) =     25.913 ms/op
     p(99.9999) =     26.051 ms/op
    p(100.0000) =     26.051 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.600 ± 2.828  ops/ms
ClientPb.existUser                       thrpt       3  10.123 ± 1.107  ops/ms
ClientPb.getUser                         thrpt       3   9.678 ± 1.316  ops/ms
ClientPb.listUser                        thrpt       3   8.159 ± 2.517  ops/ms
ClientPb.createUser                       avgt       3   3.284 ± 1.104   ms/op
ClientPb.existUser                        avgt       3   3.144 ± 0.694   ms/op
ClientPb.getUser                          avgt       3   3.272 ± 0.481   ms/op
ClientPb.listUser                         avgt       3   3.839 ± 1.279   ms/op
ClientPb.createUser                     sample  288607   3.322 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.184           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.252           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.727           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.018           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.718           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.810           ms/op
ClientPb.createUser:createUser·p0.9999  sample          22.755           ms/op
ClientPb.createUser:createUser·p1.00    sample          24.871           ms/op
ClientPb.existUser                      sample  304390   3.154 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.929           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.092           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.424           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.670           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.603           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.183           ms/op
ClientPb.existUser:existUser·p0.9999    sample          23.507           ms/op
ClientPb.existUser:existUser·p1.00      sample          25.919           ms/op
ClientPb.getUser                        sample  287111   3.340 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.098           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.248           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.744           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.145           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.136           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.350           ms/op
ClientPb.getUser:getUser·p0.9999        sample          23.373           ms/op
ClientPb.getUser:getUser·p1.00          sample          25.068           ms/op
ClientPb.listUser                       sample  245879   3.902 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.067           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.748           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.276           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.620           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.430           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.189           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.554           ms/op
ClientPb.listUser:listUser·p1.00        sample          26.051           ms/op
