# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.195 ops/ms
# Warmup Iteration   2: 6.476 ops/ms
# Warmup Iteration   3: 7.795 ops/ms
Iteration   1: 8.571 ops/ms
Iteration   2: 8.398 ops/ms
Iteration   3: 8.180 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.383 ±(99.9%) 3.578 ops/ms [Average]
  (min, avg, max) = (8.180, 8.383, 8.571), stdev = 0.196
  CI (99.9%): [4.805, 11.961] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 6.110 ops/ms
# Warmup Iteration   2: 8.254 ops/ms
# Warmup Iteration   3: 8.663 ops/ms
Iteration   1: 8.781 ops/ms
Iteration   2: 8.917 ops/ms
Iteration   3: 9.008 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.902 ±(99.9%) 2.083 ops/ms [Average]
  (min, avg, max) = (8.781, 8.902, 9.008), stdev = 0.114
  CI (99.9%): [6.819, 10.985] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 5.105 ops/ms
# Warmup Iteration   2: 7.970 ops/ms
# Warmup Iteration   3: 8.303 ops/ms
Iteration   1: 8.525 ops/ms
Iteration   2: 8.674 ops/ms
Iteration   3: 8.417 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.539 ±(99.9%) 2.351 ops/ms [Average]
  (min, avg, max) = (8.417, 8.539, 8.674), stdev = 0.129
  CI (99.9%): [6.187, 10.890] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 4.400 ops/ms
# Warmup Iteration   2: 5.921 ops/ms
# Warmup Iteration   3: 6.173 ops/ms
Iteration   1: 6.521 ops/ms
Iteration   2: 6.612 ops/ms
Iteration   3: 6.610 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.581 ±(99.9%) 0.949 ops/ms [Average]
  (min, avg, max) = (6.521, 6.581, 6.612), stdev = 0.052
  CI (99.9%): [5.632, 7.531] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 5.401 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 4.010 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.901 ±(99.9%) 0.007 ms/op
Iteration   1: 3.779 ±(99.9%) 0.003 ms/op
Iteration   2: 3.788 ±(99.9%) 0.004 ms/op
Iteration   3: 3.751 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.772 ±(99.9%) 0.357 ms/op [Average]
  (min, avg, max) = (3.751, 3.772, 3.788), stdev = 0.020
  CI (99.9%): [3.415, 4.129] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 4.898 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.704 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.552 ±(99.9%) 0.005 ms/op
Iteration   1: 3.627 ±(99.9%) 0.003 ms/op
Iteration   2: 3.647 ±(99.9%) 0.004 ms/op
Iteration   3: 3.580 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.618 ±(99.9%) 0.630 ms/op [Average]
  (min, avg, max) = (3.580, 3.618, 3.647), stdev = 0.035
  CI (99.9%): [2.988, 4.248] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 5.062 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.921 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.751 ±(99.9%) 0.003 ms/op
Iteration   1: 3.709 ±(99.9%) 0.002 ms/op
Iteration   2: 3.643 ±(99.9%) 0.003 ms/op
Iteration   3: 3.775 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.709 ±(99.9%) 1.201 ms/op [Average]
  (min, avg, max) = (3.643, 3.709, 3.775), stdev = 0.066
  CI (99.9%): [2.508, 4.910] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 6.275 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 5.285 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 5.020 ±(99.9%) 0.017 ms/op
Iteration   1: 4.793 ±(99.9%) 0.019 ms/op
Iteration   2: 4.790 ±(99.9%) 0.014 ms/op
Iteration   3: 4.725 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.769 ±(99.9%) 0.697 ms/op [Average]
  (min, avg, max) = (4.725, 4.769, 4.793), stdev = 0.038
  CI (99.9%): [4.073, 5.466] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 5.162 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 4.055 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.887 ±(99.9%) 0.011 ms/op
Iteration   1: 3.788 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.763 ms/op
                 createUser·p0.50:   3.715 ms/op
                 createUser·p0.90:   4.415 ms/op
                 createUser·p0.95:   4.727 ms/op
                 createUser·p0.99:   6.291 ms/op
                 createUser·p0.999:  9.686 ms/op
                 createUser·p0.9999: 17.433 ms/op
                 createUser·p1.00:   17.891 ms/op

Iteration   2: 3.847 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   0.857 ms/op
                 createUser·p0.50:   3.768 ms/op
                 createUser·p0.90:   4.596 ms/op
                 createUser·p0.95:   4.915 ms/op
                 createUser·p0.99:   6.234 ms/op
                 createUser·p0.999:  13.074 ms/op
                 createUser·p0.9999: 40.042 ms/op
                 createUser·p1.00:   40.567 ms/op

Iteration   3: 3.782 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   0.836 ms/op
                 createUser·p0.50:   3.686 ms/op
                 createUser·p0.90:   4.432 ms/op
                 createUser·p0.95:   4.817 ms/op
                 createUser·p0.99:   6.988 ms/op
                 createUser·p0.999:  20.362 ms/op
                 createUser·p0.9999: 29.083 ms/op
                 createUser·p1.00:   29.229 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 252059
  mean =      3.806 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 242739 
    [ 5.000, 10.000) = 8866 
    [10.000, 15.000) = 260 
    [15.000, 20.000) = 35 
    [20.000, 25.000) = 95 
    [25.000, 30.000) = 32 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 23 
    [40.000, 45.000) = 9 

  Percentiles, ms/op:
      p(0.0000) =      0.763 ms/op
     p(50.0000) =      3.723 ms/op
     p(90.0000) =      4.489 ms/op
     p(95.0000) =      4.833 ms/op
     p(99.0000) =      6.382 ms/op
     p(99.9000) =     12.616 ms/op
     p(99.9900) =     39.505 ms/op
     p(99.9990) =     40.367 ms/op
     p(99.9999) =     40.567 ms/op
    p(100.0000) =     40.567 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.173 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 3.775 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.664 ±(99.9%) 0.008 ms/op
Iteration   1: 3.520 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.791 ms/op
                 existUser·p0.50:   3.478 ms/op
                 existUser·p0.90:   4.116 ms/op
                 existUser·p0.95:   4.448 ms/op
                 existUser·p0.99:   5.456 ms/op
                 existUser·p0.999:  7.651 ms/op
                 existUser·p0.9999: 14.560 ms/op
                 existUser·p1.00:   15.106 ms/op

Iteration   2: 3.703 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.658 ms/op
                 existUser·p0.50:   3.617 ms/op
                 existUser·p0.90:   4.440 ms/op
                 existUser·p0.95:   4.751 ms/op
                 existUser·p0.99:   5.997 ms/op
                 existUser·p0.999:  13.517 ms/op
                 existUser·p0.9999: 16.592 ms/op
                 existUser·p1.00:   16.876 ms/op

Iteration   3: 3.533 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.811 ms/op
                 existUser·p0.50:   3.486 ms/op
                 existUser·p0.90:   4.149 ms/op
                 existUser·p0.95:   4.448 ms/op
                 existUser·p0.99:   5.374 ms/op
                 existUser·p0.999:  8.397 ms/op
                 existUser·p0.9999: 18.185 ms/op
                 existUser·p1.00:   19.268 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 267741
  mean =      3.583 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 163 
    [ 1.250,  2.500) = 7007 
    [ 2.500,  3.750) = 177984 
    [ 3.750,  5.000) = 76882 
    [ 5.000,  6.250) = 4135 
    [ 6.250,  7.500) = 870 
    [ 7.500,  8.750) = 411 
    [ 8.750, 10.000) = 63 
    [10.000, 11.250) = 63 
    [11.250, 12.500) = 2 
    [12.500, 13.750) = 28 
    [13.750, 15.000) = 67 
    [15.000, 16.250) = 23 
    [16.250, 17.500) = 19 
    [17.500, 18.750) = 17 

  Percentiles, ms/op:
      p(0.0000) =      0.658 ms/op
     p(50.0000) =      3.523 ms/op
     p(90.0000) =      4.260 ms/op
     p(95.0000) =      4.571 ms/op
     p(99.0000) =      5.612 ms/op
     p(99.9000) =      9.331 ms/op
     p(99.9900) =     17.374 ms/op
     p(99.9990) =     19.213 ms/op
     p(99.9999) =     19.268 ms/op
    p(100.0000) =     19.268 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.047 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 3.965 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.834 ±(99.9%) 0.010 ms/op
Iteration   1: 3.762 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.075 ms/op
                 getUser·p0.50:   3.686 ms/op
                 getUser·p0.90:   4.579 ms/op
                 getUser·p0.95:   4.891 ms/op
                 getUser·p0.99:   5.988 ms/op
                 getUser·p0.999:  12.202 ms/op
                 getUser·p0.9999: 16.383 ms/op
                 getUser·p1.00:   17.072 ms/op

Iteration   2: 3.795 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.104 ms/op
                 getUser·p0.50:   3.715 ms/op
                 getUser·p0.90:   4.514 ms/op
                 getUser·p0.95:   4.833 ms/op
                 getUser·p0.99:   5.988 ms/op
                 getUser·p0.999:  10.252 ms/op
                 getUser·p0.9999: 19.647 ms/op
                 getUser·p1.00:   20.316 ms/op

Iteration   3: 3.791 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.840 ms/op
                 getUser·p0.50:   3.707 ms/op
                 getUser·p0.90:   4.506 ms/op
                 getUser·p0.95:   4.817 ms/op
                 getUser·p0.99:   6.120 ms/op
                 getUser·p0.999:  11.847 ms/op
                 getUser·p0.9999: 21.744 ms/op
                 getUser·p1.00:   22.249 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 253690
  mean =      3.783 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5479 
    [ 2.500,  5.000) = 238885 
    [ 5.000,  7.500) = 8206 
    [ 7.500, 10.000) = 735 
    [10.000, 12.500) = 220 
    [12.500, 15.000) = 33 
    [15.000, 17.500) = 36 
    [17.500, 20.000) = 40 
    [20.000, 22.500) = 56 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.840 ms/op
     p(50.0000) =      3.703 ms/op
     p(90.0000) =      4.530 ms/op
     p(95.0000) =      4.850 ms/op
     p(99.0000) =      6.029 ms/op
     p(99.9000) =     11.184 ms/op
     p(99.9900) =     21.549 ms/op
     p(99.9990) =     22.249 ms/op
     p(99.9999) =     22.249 ms/op
    p(100.0000) =     22.249 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 5.735 ±(99.9%) 0.065 ms/op
# Warmup Iteration   2: 5.283 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.823 ±(99.9%) 0.016 ms/op
Iteration   1: 4.979 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.208 ms/op
                 listUser·p0.50:   4.702 ms/op
                 listUser·p0.90:   6.480 ms/op
                 listUser·p0.95:   7.438 ms/op
                 listUser·p0.99:   9.496 ms/op
                 listUser·p0.999:  16.002 ms/op
                 listUser·p0.9999: 28.302 ms/op
                 listUser·p1.00:   31.490 ms/op

Iteration   2: 4.714 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.434 ms/op
                 listUser·p0.50:   4.506 ms/op
                 listUser·p0.90:   5.980 ms/op
                 listUser·p0.95:   6.734 ms/op
                 listUser·p0.99:   8.552 ms/op
                 listUser·p0.999:  15.928 ms/op
                 listUser·p0.9999: 18.711 ms/op
                 listUser·p1.00:   25.362 ms/op

Iteration   3: 4.848 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.143 ms/op
                 listUser·p0.50:   4.628 ms/op
                 listUser·p0.90:   6.054 ms/op
                 listUser·p0.95:   7.111 ms/op
                 listUser·p0.99:   8.716 ms/op
                 listUser·p0.999:  19.137 ms/op
                 listUser·p0.9999: 24.570 ms/op
                 listUser·p1.00:   25.133 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 198140
  mean =      4.845 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 256 
    [ 2.500,  5.000) = 142026 
    [ 5.000,  7.500) = 48612 
    [ 7.500, 10.000) = 6253 
    [10.000, 12.500) = 540 
    [12.500, 15.000) = 116 
    [15.000, 17.500) = 184 
    [17.500, 20.000) = 64 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 10 
    [27.500, 30.000) = 21 
    [30.000, 32.500) = 3 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.143 ms/op
     p(50.0000) =      4.612 ms/op
     p(90.0000) =      6.169 ms/op
     p(95.0000) =      7.119 ms/op
     p(99.0000) =      8.913 ms/op
     p(99.9000) =     16.400 ms/op
     p(99.9900) =     27.722 ms/op
     p(99.9990) =     31.329 ms/op
     p(99.9999) =     31.490 ms/op
    p(100.0000) =     31.490 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.383 ± 3.578  ops/ms
ClientGrpc.existUser                       thrpt       3   8.902 ± 2.083  ops/ms
ClientGrpc.getUser                         thrpt       3   8.539 ± 2.351  ops/ms
ClientGrpc.listUser                        thrpt       3   6.581 ± 0.949  ops/ms
ClientGrpc.createUser                       avgt       3   3.772 ± 0.357   ms/op
ClientGrpc.existUser                        avgt       3   3.618 ± 0.630   ms/op
ClientGrpc.getUser                          avgt       3   3.709 ± 1.201   ms/op
ClientGrpc.listUser                         avgt       3   4.769 ± 0.697   ms/op
ClientGrpc.createUser                     sample  252059   3.806 ± 0.006   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.763           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.723           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.489           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.833           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.382           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.616           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          39.505           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          40.567           ms/op
ClientGrpc.existUser                      sample  267741   3.583 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.658           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.523           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.260           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.571           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.612           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           9.331           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.374           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          19.268           ms/op
ClientGrpc.getUser                        sample  253690   3.783 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.840           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.703           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.530           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.850           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.029           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          11.184           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          21.549           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          22.249           ms/op
ClientGrpc.listUser                       sample  198140   4.845 ± 0.009   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.143           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.612           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.169           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.119           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.913           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.400           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          27.722           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          31.490           ms/op
