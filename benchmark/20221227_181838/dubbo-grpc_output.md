# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.124 ops/ms
# Warmup Iteration   2: 5.494 ops/ms
# Warmup Iteration   3: 6.932 ops/ms
Iteration   1: 7.370 ops/ms
Iteration   2: 7.428 ops/ms
Iteration   3: 7.497 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.432 ±(99.9%) 1.161 ops/ms [Average]
  (min, avg, max) = (7.370, 7.432, 7.497), stdev = 0.064
  CI (99.9%): [6.271, 8.592] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:12:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.843 ops/ms
# Warmup Iteration   2: 7.476 ops/ms
# Warmup Iteration   3: 7.576 ops/ms
Iteration   1: 8.109 ops/ms
Iteration   2: 7.976 ops/ms
Iteration   3: 8.203 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.096 ±(99.9%) 2.082 ops/ms [Average]
  (min, avg, max) = (7.976, 8.096, 8.203), stdev = 0.114
  CI (99.9%): [6.014, 10.178] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:58
# Fork: 1 of 1
# Warmup Iteration   1: 4.036 ops/ms
# Warmup Iteration   2: 6.540 ops/ms
# Warmup Iteration   3: 7.175 ops/ms
Iteration   1: 7.360 ops/ms
Iteration   2: 7.614 ops/ms
Iteration   3: 7.453 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.476 ±(99.9%) 2.345 ops/ms [Average]
  (min, avg, max) = (7.360, 7.476, 7.614), stdev = 0.129
  CI (99.9%): [5.131, 9.821] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 4.010 ops/ms
# Warmup Iteration   2: 5.296 ops/ms
# Warmup Iteration   3: 5.391 ops/ms
Iteration   1: 5.424 ops/ms
Iteration   2: 5.493 ops/ms
Iteration   3: 5.546 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.488 ±(99.9%) 1.116 ops/ms [Average]
  (min, avg, max) = (5.424, 5.488, 5.546), stdev = 0.061
  CI (99.9%): [4.372, 6.603] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 6.807 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 4.631 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 4.466 ±(99.9%) 0.027 ms/op
Iteration   1: 4.395 ±(99.9%) 0.002 ms/op
Iteration   2: 4.319 ±(99.9%) 0.003 ms/op
Iteration   3: 4.341 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.351 ±(99.9%) 0.712 ms/op [Average]
  (min, avg, max) = (4.319, 4.351, 4.395), stdev = 0.039
  CI (99.9%): [3.640, 5.063] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 6.224 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 4.316 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.047 ±(99.9%) 0.004 ms/op
Iteration   1: 3.946 ±(99.9%) 0.003 ms/op
Iteration   2: 4.078 ±(99.9%) 0.004 ms/op
Iteration   3: 4.087 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.037 ±(99.9%) 1.443 ms/op [Average]
  (min, avg, max) = (3.946, 4.037, 4.087), stdev = 0.079
  CI (99.9%): [2.594, 5.480] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 6.780 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 4.615 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.470 ±(99.9%) 0.006 ms/op
Iteration   1: 4.252 ±(99.9%) 0.006 ms/op
Iteration   2: 4.384 ±(99.9%) 0.004 ms/op
Iteration   3: 4.457 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.364 ±(99.9%) 1.900 ms/op [Average]
  (min, avg, max) = (4.252, 4.364, 4.457), stdev = 0.104
  CI (99.9%): [2.465, 6.264] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 8.131 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 5.965 ±(99.9%) 0.035 ms/op
# Warmup Iteration   3: 5.571 ±(99.9%) 0.024 ms/op
Iteration   1: 5.604 ±(99.9%) 0.022 ms/op
Iteration   2: 5.571 ±(99.9%) 0.020 ms/op
Iteration   3: 5.496 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.557 ±(99.9%) 1.010 ms/op [Average]
  (min, avg, max) = (5.496, 5.557, 5.604), stdev = 0.055
  CI (99.9%): [4.547, 6.567] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 6.423 ±(99.9%) 0.075 ms/op
# Warmup Iteration   2: 4.572 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.501 ±(99.9%) 0.014 ms/op
Iteration   1: 4.466 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   0.892 ms/op
                 createUser·p0.50:   4.309 ms/op
                 createUser·p0.90:   5.669 ms/op
                 createUser·p0.95:   6.177 ms/op
                 createUser·p0.99:   8.145 ms/op
                 createUser·p0.999:  13.188 ms/op
                 createUser·p0.9999: 15.824 ms/op
                 createUser·p1.00:   16.171 ms/op

Iteration   2: 4.417 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   0.822 ms/op
                 createUser·p0.50:   4.284 ms/op
                 createUser·p0.90:   5.513 ms/op
                 createUser·p0.95:   5.972 ms/op
                 createUser·p0.99:   8.602 ms/op
                 createUser·p0.999:  13.146 ms/op
                 createUser·p0.9999: 17.515 ms/op
                 createUser·p1.00:   17.793 ms/op

Iteration   3: 4.388 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   0.877 ms/op
                 createUser·p0.50:   4.235 ms/op
                 createUser·p0.90:   5.546 ms/op
                 createUser·p0.95:   6.046 ms/op
                 createUser·p0.99:   8.069 ms/op
                 createUser·p0.999:  14.556 ms/op
                 createUser·p0.9999: 22.835 ms/op
                 createUser·p1.00:   23.331 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 216946
  mean =      4.423 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2346 
    [ 2.500,  5.000) = 166737 
    [ 5.000,  7.500) = 44510 
    [ 7.500, 10.000) = 2578 
    [10.000, 12.500) = 477 
    [12.500, 15.000) = 144 
    [15.000, 17.500) = 94 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.822 ms/op
     p(50.0000) =      4.276 ms/op
     p(90.0000) =      5.579 ms/op
     p(95.0000) =      6.070 ms/op
     p(99.0000) =      8.249 ms/op
     p(99.9000) =     13.600 ms/op
     p(99.9900) =     21.013 ms/op
     p(99.9990) =     23.227 ms/op
     p(99.9999) =     23.331 ms/op
    p(100.0000) =     23.331 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 6.212 ±(99.9%) 0.067 ms/op
# Warmup Iteration   2: 4.494 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.295 ±(99.9%) 0.013 ms/op
Iteration   1: 4.295 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   0.391 ms/op
                 existUser·p0.50:   4.145 ms/op
                 existUser·p0.90:   5.423 ms/op
                 existUser·p0.95:   6.005 ms/op
                 existUser·p0.99:   8.520 ms/op
                 existUser·p0.999:  13.197 ms/op
                 existUser·p0.9999: 14.858 ms/op
                 existUser·p1.00:   15.368 ms/op

Iteration   2: 4.196 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   0.753 ms/op
                 existUser·p0.50:   4.035 ms/op
                 existUser·p0.90:   5.448 ms/op
                 existUser·p0.95:   5.906 ms/op
                 existUser·p0.99:   8.077 ms/op
                 existUser·p0.999:  16.843 ms/op
                 existUser·p0.9999: 24.752 ms/op
                 existUser·p1.00:   26.575 ms/op

Iteration   3: 4.085 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.900 ms/op
                 existUser·p0.50:   3.998 ms/op
                 existUser·p0.90:   5.218 ms/op
                 existUser·p0.95:   5.628 ms/op
                 existUser·p0.99:   7.324 ms/op
                 existUser·p0.999:  10.896 ms/op
                 existUser·p0.9999: 18.656 ms/op
                 existUser·p1.00:   19.890 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 229116
  mean =      4.190 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7875 
    [ 2.500,  5.000) = 182706 
    [ 5.000,  7.500) = 35615 
    [ 7.500, 10.000) = 2144 
    [10.000, 12.500) = 483 
    [12.500, 15.000) = 126 
    [15.000, 17.500) = 75 
    [17.500, 20.000) = 53 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      0.391 ms/op
     p(50.0000) =      4.059 ms/op
     p(90.0000) =      5.358 ms/op
     p(95.0000) =      5.841 ms/op
     p(99.0000) =      7.930 ms/op
     p(99.9000) =     13.791 ms/op
     p(99.9900) =     23.905 ms/op
     p(99.9990) =     26.444 ms/op
     p(99.9999) =     26.575 ms/op
    p(100.0000) =     26.575 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 6.741 ±(99.9%) 0.078 ms/op
# Warmup Iteration   2: 4.716 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.684 ±(99.9%) 0.017 ms/op
Iteration   1: 4.303 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.077 ms/op
                 getUser·p0.50:   4.153 ms/op
                 getUser·p0.90:   5.472 ms/op
                 getUser·p0.95:   6.062 ms/op
                 getUser·p0.99:   8.233 ms/op
                 getUser·p0.999:  14.206 ms/op
                 getUser·p0.9999: 17.121 ms/op
                 getUser·p1.00:   17.891 ms/op

Iteration   2: 4.377 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.159 ms/op
                 getUser·p0.50:   4.211 ms/op
                 getUser·p0.90:   5.539 ms/op
                 getUser·p0.95:   6.087 ms/op
                 getUser·p0.99:   8.225 ms/op
                 getUser·p0.999:  12.118 ms/op
                 getUser·p0.9999: 18.843 ms/op
                 getUser·p1.00:   19.497 ms/op

Iteration   3: 4.240 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   0.562 ms/op
                 getUser·p0.50:   4.116 ms/op
                 getUser·p0.90:   5.333 ms/op
                 getUser·p0.95:   5.931 ms/op
                 getUser·p0.99:   8.110 ms/op
                 getUser·p0.999:  11.158 ms/op
                 getUser·p0.9999: 20.775 ms/op
                 getUser·p1.00:   21.299 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 223076
  mean =      4.306 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5533 
    [ 2.500,  5.000) = 177567 
    [ 5.000,  7.500) = 36632 
    [ 7.500, 10.000) = 2674 
    [10.000, 12.500) = 441 
    [12.500, 15.000) = 94 
    [15.000, 17.500) = 69 
    [17.500, 20.000) = 44 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.562 ms/op
     p(50.0000) =      4.157 ms/op
     p(90.0000) =      5.456 ms/op
     p(95.0000) =      6.021 ms/op
     p(99.0000) =      8.184 ms/op
     p(99.9000) =     12.567 ms/op
     p(99.9900) =     20.034 ms/op
     p(99.9990) =     21.072 ms/op
     p(99.9999) =     21.299 ms/op
    p(100.0000) =     21.299 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 7.636 ±(99.9%) 0.096 ms/op
# Warmup Iteration   2: 6.238 ±(99.9%) 0.030 ms/op
# Warmup Iteration   3: 5.831 ±(99.9%) 0.025 ms/op
Iteration   1: 5.751 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   1.534 ms/op
                 listUser·p0.50:   5.325 ms/op
                 listUser·p0.90:   7.922 ms/op
                 listUser·p0.95:   9.044 ms/op
                 listUser·p0.99:   11.321 ms/op
                 listUser·p0.999:  17.904 ms/op
                 listUser·p0.9999: 21.150 ms/op
                 listUser·p1.00:   21.922 ms/op

Iteration   2: 5.545 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   1.528 ms/op
                 listUser·p0.50:   5.136 ms/op
                 listUser·p0.90:   7.807 ms/op
                 listUser·p0.95:   8.815 ms/op
                 listUser·p0.99:   10.895 ms/op
                 listUser·p0.999:  18.755 ms/op
                 listUser·p0.9999: 23.101 ms/op
                 listUser·p1.00:   26.804 ms/op

Iteration   3: 5.744 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   1.321 ms/op
                 listUser·p0.50:   5.382 ms/op
                 listUser·p0.90:   7.905 ms/op
                 listUser·p0.95:   8.880 ms/op
                 listUser·p0.99:   11.195 ms/op
                 listUser·p0.999:  22.315 ms/op
                 listUser·p0.9999: 28.326 ms/op
                 listUser·p1.00:   29.983 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 168946
  mean =      5.679 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 372 
    [ 2.500,  5.000) = 70362 
    [ 5.000,  7.500) = 76340 
    [ 7.500, 10.000) = 17962 
    [10.000, 12.500) = 3125 
    [12.500, 15.000) = 390 
    [15.000, 17.500) = 138 
    [17.500, 20.000) = 96 
    [20.000, 22.500) = 109 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 14 

  Percentiles, ms/op:
      p(0.0000) =      1.321 ms/op
     p(50.0000) =      5.276 ms/op
     p(90.0000) =      7.881 ms/op
     p(95.0000) =      8.913 ms/op
     p(99.0000) =     11.158 ms/op
     p(99.9000) =     19.825 ms/op
     p(99.9900) =     25.904 ms/op
     p(99.9990) =     29.192 ms/op
     p(99.9999) =     29.983 ms/op
    p(100.0000) =     29.983 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.432 ± 1.161  ops/ms
ClientGrpc.existUser                       thrpt       3   8.096 ± 2.082  ops/ms
ClientGrpc.getUser                         thrpt       3   7.476 ± 2.345  ops/ms
ClientGrpc.listUser                        thrpt       3   5.488 ± 1.116  ops/ms
ClientGrpc.createUser                       avgt       3   4.351 ± 0.712   ms/op
ClientGrpc.existUser                        avgt       3   4.037 ± 1.443   ms/op
ClientGrpc.getUser                          avgt       3   4.364 ± 1.900   ms/op
ClientGrpc.listUser                         avgt       3   5.557 ± 1.010   ms/op
ClientGrpc.createUser                     sample  216946   4.423 ± 0.008   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.822           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.276           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.579           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           6.070           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           8.249           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          13.600           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.013           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          23.331           ms/op
ClientGrpc.existUser                      sample  229116   4.190 ± 0.008   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.391           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           4.059           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.358           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.841           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           7.930           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          13.791           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          23.905           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          26.575           ms/op
ClientGrpc.getUser                        sample  223076   4.306 ± 0.008   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.562           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.157           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.456           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           6.021           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           8.184           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          12.567           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          20.034           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          21.299           ms/op
ClientGrpc.listUser                       sample  168946   5.679 ± 0.014   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.321           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.276           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.881           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           8.913           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          11.158           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          19.825           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.904           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          29.983           ms/op
