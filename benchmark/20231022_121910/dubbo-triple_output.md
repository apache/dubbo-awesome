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
# Warmup Iteration   1: 2.397 ops/ms
# Warmup Iteration   2: 6.166 ops/ms
# Warmup Iteration   3: 9.134 ops/ms
Iteration   1: 9.514 ops/ms
Iteration   2: 9.597 ops/ms
Iteration   3: 9.844 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.652 ±(99.9%) 3.135 ops/ms [Average]
  (min, avg, max) = (9.514, 9.652, 9.844), stdev = 0.172
  CI (99.9%): [6.516, 12.787] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 3.777 ops/ms
# Warmup Iteration   2: 9.579 ops/ms
# Warmup Iteration   3: 10.013 ops/ms
Iteration   1: 10.411 ops/ms
Iteration   2: 10.144 ops/ms
Iteration   3: 9.944 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.166 ±(99.9%) 4.278 ops/ms [Average]
  (min, avg, max) = (9.944, 10.166, 10.411), stdev = 0.234
  CI (99.9%): [5.888, 14.444] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 3.329 ops/ms
# Warmup Iteration   2: 9.080 ops/ms
# Warmup Iteration   3: 9.693 ops/ms
Iteration   1: 9.717 ops/ms
Iteration   2: 10.057 ops/ms
Iteration   3: 9.782 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.852 ±(99.9%) 3.297 ops/ms [Average]
  (min, avg, max) = (9.717, 9.852, 10.057), stdev = 0.181
  CI (99.9%): [6.555, 13.149] (assumes normal distribution)


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
# Warmup Iteration   1: 3.023 ops/ms
# Warmup Iteration   2: 7.539 ops/ms
# Warmup Iteration   3: 8.225 ops/ms
Iteration   1: 8.271 ops/ms
Iteration   2: 8.224 ops/ms
Iteration   3: 8.147 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.214 ±(99.9%) 1.135 ops/ms [Average]
  (min, avg, max) = (8.147, 8.214, 8.271), stdev = 0.062
  CI (99.9%): [7.079, 9.349] (assumes normal distribution)


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
# Warmup Iteration   1: 8.065 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.434 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.433 ±(99.9%) 0.003 ms/op
Iteration   1: 3.265 ±(99.9%) 0.004 ms/op
Iteration   2: 3.282 ±(99.9%) 0.002 ms/op
Iteration   3: 3.166 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.238 ±(99.9%) 1.140 ms/op [Average]
  (min, avg, max) = (3.166, 3.238, 3.282), stdev = 0.063
  CI (99.9%): [2.098, 4.378] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 7.601 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.350 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.124 ±(99.9%) 0.003 ms/op
Iteration   1: 3.158 ±(99.9%) 0.005 ms/op
Iteration   2: 3.079 ±(99.9%) 0.002 ms/op
Iteration   3: 3.120 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.119 ±(99.9%) 0.719 ms/op [Average]
  (min, avg, max) = (3.079, 3.119, 3.158), stdev = 0.039
  CI (99.9%): [2.400, 3.838] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 8.021 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.381 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.335 ±(99.9%) 0.003 ms/op
Iteration   1: 3.211 ±(99.9%) 0.004 ms/op
Iteration   2: 3.225 ±(99.9%) 0.003 ms/op
Iteration   3: 3.234 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.223 ±(99.9%) 0.214 ms/op [Average]
  (min, avg, max) = (3.211, 3.223, 3.234), stdev = 0.012
  CI (99.9%): [3.010, 3.437] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 9.740 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 4.201 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.935 ±(99.9%) 0.004 ms/op
Iteration   1: 3.946 ±(99.9%) 0.004 ms/op
Iteration   2: 3.864 ±(99.9%) 0.004 ms/op
Iteration   3: 3.845 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.885 ±(99.9%) 0.982 ms/op [Average]
  (min, avg, max) = (3.845, 3.885, 3.946), stdev = 0.054
  CI (99.9%): [2.903, 4.867] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 8.338 ±(99.9%) 0.096 ms/op
# Warmup Iteration   2: 3.625 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.266 ±(99.9%) 0.008 ms/op
Iteration   1: 3.244 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.037 ms/op
                 createUser·p0.50:   3.187 ms/op
                 createUser·p0.90:   3.600 ms/op
                 createUser·p0.95:   3.899 ms/op
                 createUser·p0.99:   5.759 ms/op
                 createUser·p0.999:  19.198 ms/op
                 createUser·p0.9999: 21.669 ms/op
                 createUser·p1.00:   22.643 ms/op

Iteration   2: 3.249 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.438 ms/op
                 createUser·p0.50:   3.121 ms/op
                 createUser·p0.90:   3.654 ms/op
                 createUser·p0.95:   3.920 ms/op
                 createUser·p0.99:   5.489 ms/op
                 createUser·p0.999:  17.740 ms/op
                 createUser·p0.9999: 22.990 ms/op
                 createUser·p1.00:   25.559 ms/op

Iteration   3: 3.275 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.647 ms/op
                 createUser·p0.50:   3.207 ms/op
                 createUser·p0.90:   3.703 ms/op
                 createUser·p0.95:   3.928 ms/op
                 createUser·p0.99:   4.981 ms/op
                 createUser·p0.999:  15.345 ms/op
                 createUser·p0.9999: 19.330 ms/op
                 createUser·p1.00:   19.956 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 294695
  mean =      3.256 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12136 
    [ 2.500,  5.000) = 278830 
    [ 5.000,  7.500) = 2738 
    [ 7.500, 10.000) = 313 
    [10.000, 12.500) = 220 
    [12.500, 15.000) = 92 
    [15.000, 17.500) = 81 
    [17.500, 20.000) = 116 
    [20.000, 22.500) = 146 
    [22.500, 25.000) = 22 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.647 ms/op
     p(50.0000) =      3.174 ms/op
     p(90.0000) =      3.666 ms/op
     p(95.0000) =      3.916 ms/op
     p(99.0000) =      5.448 ms/op
     p(99.9000) =     17.400 ms/op
     p(99.9900) =     22.201 ms/op
     p(99.9990) =     24.022 ms/op
     p(99.9999) =     25.559 ms/op
    p(100.0000) =     25.559 ms/op


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
# Warmup Iteration   1: 7.984 ±(99.9%) 0.095 ms/op
# Warmup Iteration   2: 3.443 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.159 ±(99.9%) 0.007 ms/op
Iteration   1: 3.095 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.239 ms/op
                 existUser·p0.50:   2.994 ms/op
                 existUser·p0.90:   3.363 ms/op
                 existUser·p0.95:   3.572 ms/op
                 existUser·p0.99:   5.366 ms/op
                 existUser·p0.999:  13.489 ms/op
                 existUser·p0.9999: 20.644 ms/op
                 existUser·p1.00:   21.299 ms/op

Iteration   2: 3.116 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.194 ms/op
                 existUser·p0.50:   3.125 ms/op
                 existUser·p0.90:   3.334 ms/op
                 existUser·p0.95:   3.555 ms/op
                 existUser·p0.99:   4.733 ms/op
                 existUser·p0.999:  14.973 ms/op
                 existUser·p0.9999: 23.060 ms/op
                 existUser·p1.00:   23.822 ms/op

Iteration   3: 3.137 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.100 ms/op
                 existUser·p0.50:   3.052 ms/op
                 existUser·p0.90:   3.424 ms/op
                 existUser·p0.95:   3.645 ms/op
                 existUser·p0.99:   5.292 ms/op
                 existUser·p0.999:  13.598 ms/op
                 existUser·p0.9999: 22.151 ms/op
                 existUser·p1.00:   22.872 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 307877
  mean =      3.116 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13500 
    [ 2.500,  5.000) = 290546 
    [ 5.000,  7.500) = 3126 
    [ 7.500, 10.000) = 213 
    [10.000, 12.500) = 139 
    [12.500, 15.000) = 90 
    [15.000, 17.500) = 37 
    [17.500, 20.000) = 77 
    [20.000, 22.500) = 124 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.100 ms/op
     p(50.0000) =      3.056 ms/op
     p(90.0000) =      3.375 ms/op
     p(95.0000) =      3.592 ms/op
     p(99.0000) =      5.251 ms/op
     p(99.9000) =     13.607 ms/op
     p(99.9900) =     22.362 ms/op
     p(99.9990) =     23.394 ms/op
     p(99.9999) =     23.822 ms/op
    p(100.0000) =     23.822 ms/op


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
# Warmup Iteration   1: 9.006 ±(99.9%) 0.100 ms/op
# Warmup Iteration   2: 3.458 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.246 ±(99.9%) 0.008 ms/op
Iteration   1: 3.369 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.042 ms/op
                 getUser·p0.50:   3.203 ms/op
                 getUser·p0.90:   3.690 ms/op
                 getUser·p0.95:   4.407 ms/op
                 getUser·p0.99:   6.824 ms/op
                 getUser·p0.999:  18.022 ms/op
                 getUser·p0.9999: 20.122 ms/op
                 getUser·p1.00:   21.135 ms/op

Iteration   2: 3.209 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.204 ms/op
                 getUser·p0.50:   3.121 ms/op
                 getUser·p0.90:   3.506 ms/op
                 getUser·p0.95:   3.662 ms/op
                 getUser·p0.99:   5.530 ms/op
                 getUser·p0.999:  15.197 ms/op
                 getUser·p0.9999: 21.792 ms/op
                 getUser·p1.00:   22.348 ms/op

Iteration   3: 3.238 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.575 ms/op
                 getUser·p0.50:   3.162 ms/op
                 getUser·p0.90:   3.547 ms/op
                 getUser·p0.95:   3.744 ms/op
                 getUser·p0.99:   5.636 ms/op
                 getUser·p0.999:  14.293 ms/op
                 getUser·p0.9999: 19.759 ms/op
                 getUser·p1.00:   20.677 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 293124
  mean =      3.271 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7225 
    [ 2.500,  5.000) = 279163 
    [ 5.000,  7.500) = 5522 
    [ 7.500, 10.000) = 497 
    [10.000, 12.500) = 199 
    [12.500, 15.000) = 131 
    [15.000, 17.500) = 117 
    [17.500, 20.000) = 172 
    [20.000, 22.500) = 98 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.042 ms/op
     p(50.0000) =      3.162 ms/op
     p(90.0000) =      3.576 ms/op
     p(95.0000) =      3.834 ms/op
     p(99.0000) =      6.300 ms/op
     p(99.9000) =     17.105 ms/op
     p(99.9900) =     21.070 ms/op
     p(99.9990) =     22.221 ms/op
     p(99.9999) =     22.348 ms/op
    p(100.0000) =     22.348 ms/op


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
# Warmup Iteration   1: 9.372 ±(99.9%) 0.117 ms/op
# Warmup Iteration   2: 4.215 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.934 ±(99.9%) 0.011 ms/op
Iteration   1: 3.874 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.804 ms/op
                 listUser·p0.50:   3.731 ms/op
                 listUser·p0.90:   4.243 ms/op
                 listUser·p0.95:   4.432 ms/op
                 listUser·p0.99:   6.636 ms/op
                 listUser·p0.999:  16.381 ms/op
                 listUser·p0.9999: 22.543 ms/op
                 listUser·p1.00:   25.625 ms/op

Iteration   2: 3.940 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.449 ms/op
                 listUser·p0.50:   3.834 ms/op
                 listUser·p0.90:   4.358 ms/op
                 listUser·p0.95:   4.538 ms/op
                 listUser·p0.99:   6.767 ms/op
                 listUser·p0.999:  13.779 ms/op
                 listUser·p0.9999: 17.760 ms/op
                 listUser·p1.00:   20.316 ms/op

Iteration   3: 3.910 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.178 ms/op
                 listUser·p0.50:   3.801 ms/op
                 listUser·p0.90:   4.194 ms/op
                 listUser·p0.95:   4.407 ms/op
                 listUser·p0.99:   7.184 ms/op
                 listUser·p0.999:  14.746 ms/op
                 listUser·p0.9999: 15.761 ms/op
                 listUser·p1.00:   16.105 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 245577
  mean =      3.908 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 59 
    [ 2.500,  5.000) = 239246 
    [ 5.000,  7.500) = 4767 
    [ 7.500, 10.000) = 664 
    [10.000, 12.500) = 300 
    [12.500, 15.000) = 373 
    [15.000, 17.500) = 100 
    [17.500, 20.000) = 35 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.178 ms/op
     p(50.0000) =      3.789 ms/op
     p(90.0000) =      4.276 ms/op
     p(95.0000) =      4.473 ms/op
     p(99.0000) =      6.799 ms/op
     p(99.9000) =     14.647 ms/op
     p(99.9900) =     21.004 ms/op
     p(99.9990) =     23.879 ms/op
     p(99.9999) =     25.625 ms/op
    p(100.0000) =     25.625 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.652 ± 3.135  ops/ms
ClientPb.existUser                       thrpt       3  10.166 ± 4.278  ops/ms
ClientPb.getUser                         thrpt       3   9.852 ± 3.297  ops/ms
ClientPb.listUser                        thrpt       3   8.214 ± 1.135  ops/ms
ClientPb.createUser                       avgt       3   3.238 ± 1.140   ms/op
ClientPb.existUser                        avgt       3   3.119 ± 0.719   ms/op
ClientPb.getUser                          avgt       3   3.223 ± 0.214   ms/op
ClientPb.listUser                         avgt       3   3.885 ± 0.982   ms/op
ClientPb.createUser                     sample  294695   3.256 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.647           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.174           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.666           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.916           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.448           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.400           ms/op
ClientPb.createUser:createUser·p0.9999  sample          22.201           ms/op
ClientPb.createUser:createUser·p1.00    sample          25.559           ms/op
ClientPb.existUser                      sample  307877   3.116 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.100           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.056           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.375           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.592           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.251           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.607           ms/op
ClientPb.existUser:existUser·p0.9999    sample          22.362           ms/op
ClientPb.existUser:existUser·p1.00      sample          23.822           ms/op
ClientPb.getUser                        sample  293124   3.271 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.042           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.162           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.576           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.834           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.300           ms/op
ClientPb.getUser:getUser·p0.999         sample          17.105           ms/op
ClientPb.getUser:getUser·p0.9999        sample          21.070           ms/op
ClientPb.getUser:getUser·p1.00          sample          22.348           ms/op
ClientPb.listUser                       sample  245577   3.908 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.178           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.789           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.276           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.473           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.799           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.647           ms/op
ClientPb.listUser:listUser·p0.9999      sample          21.004           ms/op
ClientPb.listUser:listUser·p1.00        sample          25.625           ms/op
