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
# Warmup Iteration   1: 4.016 ops/ms
# Warmup Iteration   2: 8.833 ops/ms
# Warmup Iteration   3: 9.873 ops/ms
Iteration   1: 10.305 ops/ms
Iteration   2: 10.320 ops/ms
Iteration   3: 9.977 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.201 ±(99.9%) 3.537 ops/ms [Average]
  (min, avg, max) = (9.977, 10.201, 10.320), stdev = 0.194
  CI (99.9%): [6.664, 13.738] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 7.909 ops/ms
# Warmup Iteration   2: 10.176 ops/ms
# Warmup Iteration   3: 10.354 ops/ms
Iteration   1: 10.590 ops/ms
Iteration   2: 10.659 ops/ms
Iteration   3: 10.593 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.614 ±(99.9%) 0.707 ops/ms [Average]
  (min, avg, max) = (10.590, 10.614, 10.659), stdev = 0.039
  CI (99.9%): [9.907, 11.321] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.333 ops/ms
# Warmup Iteration   2: 9.857 ops/ms
# Warmup Iteration   3: 10.071 ops/ms
Iteration   1: 10.113 ops/ms
Iteration   2: 10.238 ops/ms
Iteration   3: 10.173 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.175 ±(99.9%) 1.143 ops/ms [Average]
  (min, avg, max) = (10.113, 10.175, 10.238), stdev = 0.063
  CI (99.9%): [9.032, 11.318] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 5.079 ops/ms
# Warmup Iteration   2: 7.572 ops/ms
# Warmup Iteration   3: 7.639 ops/ms
Iteration   1: 7.750 ops/ms
Iteration   2: 7.864 ops/ms
Iteration   3: 7.791 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.802 ±(99.9%) 1.055 ops/ms [Average]
  (min, avg, max) = (7.750, 7.802, 7.864), stdev = 0.058
  CI (99.9%): [6.747, 8.856] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.106 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.238 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.224 ±(99.9%) 0.004 ms/op
Iteration   1: 3.191 ±(99.9%) 0.002 ms/op
Iteration   2: 3.210 ±(99.9%) 0.003 ms/op
Iteration   3: 3.271 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.224 ±(99.9%) 0.762 ms/op [Average]
  (min, avg, max) = (3.191, 3.224, 3.271), stdev = 0.042
  CI (99.9%): [2.462, 3.986] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.879 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.217 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.110 ±(99.9%) 0.002 ms/op
Iteration   1: 3.031 ±(99.9%) 0.002 ms/op
Iteration   2: 3.040 ±(99.9%) 0.002 ms/op
Iteration   3: 3.047 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.040 ±(99.9%) 0.140 ms/op [Average]
  (min, avg, max) = (3.031, 3.040, 3.047), stdev = 0.008
  CI (99.9%): [2.899, 3.180] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.258 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.217 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.148 ±(99.9%) 0.002 ms/op
Iteration   1: 3.193 ±(99.9%) 0.003 ms/op
Iteration   2: 3.139 ±(99.9%) 0.002 ms/op
Iteration   3: 3.177 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.170 ±(99.9%) 0.506 ms/op [Average]
  (min, avg, max) = (3.139, 3.170, 3.193), stdev = 0.028
  CI (99.9%): [2.664, 3.675] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 5.806 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 4.169 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 4.128 ±(99.9%) 0.005 ms/op
Iteration   1: 4.108 ±(99.9%) 0.011 ms/op
Iteration   2: 4.200 ±(99.9%) 0.016 ms/op
Iteration   3: 4.049 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.119 ±(99.9%) 1.391 ms/op [Average]
  (min, avg, max) = (4.049, 4.119, 4.200), stdev = 0.076
  CI (99.9%): [2.728, 5.511] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.253 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.256 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.169 ±(99.9%) 0.006 ms/op
Iteration   1: 3.101 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.690 ms/op
                 createUser·p0.50:   3.109 ms/op
                 createUser·p0.90:   3.871 ms/op
                 createUser·p0.95:   4.076 ms/op
                 createUser·p0.99:   4.538 ms/op
                 createUser·p0.999:  8.237 ms/op
                 createUser·p0.9999: 13.697 ms/op
                 createUser·p1.00:   14.107 ms/op

Iteration   2: 3.195 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.559 ms/op
                 createUser·p0.50:   3.183 ms/op
                 createUser·p0.90:   3.916 ms/op
                 createUser·p0.95:   4.092 ms/op
                 createUser·p0.99:   4.424 ms/op
                 createUser·p0.999:  7.324 ms/op
                 createUser·p0.9999: 17.137 ms/op
                 createUser·p1.00:   17.695 ms/op

Iteration   3: 3.168 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.785 ms/op
                 createUser·p0.50:   3.117 ms/op
                 createUser·p0.90:   3.834 ms/op
                 createUser·p0.95:   4.051 ms/op
                 createUser·p0.99:   4.448 ms/op
                 createUser·p0.999:  12.894 ms/op
                 createUser·p0.9999: 22.377 ms/op
                 createUser·p1.00:   22.675 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 304402
  mean =      3.154 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 29546 
    [ 2.500,  5.000) = 273427 
    [ 5.000,  7.500) = 946 
    [ 7.500, 10.000) = 183 
    [10.000, 12.500) = 58 
    [12.500, 15.000) = 97 
    [15.000, 17.500) = 91 
    [17.500, 20.000) = 22 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 6 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.559 ms/op
     p(50.0000) =      3.133 ms/op
     p(90.0000) =      3.879 ms/op
     p(95.0000) =      4.076 ms/op
     p(99.0000) =      4.465 ms/op
     p(99.9000) =      9.873 ms/op
     p(99.9900) =     21.776 ms/op
     p(99.9990) =     22.576 ms/op
     p(99.9999) =     22.675 ms/op
    p(100.0000) =     22.675 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 4.180 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.144 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.092 ±(99.9%) 0.006 ms/op
Iteration   1: 2.977 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.472 ms/op
                 existUser·p0.50:   2.949 ms/op
                 existUser·p0.90:   3.486 ms/op
                 existUser·p0.95:   3.731 ms/op
                 existUser·p0.99:   4.440 ms/op
                 existUser·p0.999:  7.315 ms/op
                 existUser·p0.9999: 12.034 ms/op
                 existUser·p1.00:   12.435 ms/op

Iteration   2: 2.999 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.771 ms/op
                 existUser·p0.50:   3.027 ms/op
                 existUser·p0.90:   3.772 ms/op
                 existUser·p0.95:   3.924 ms/op
                 existUser·p0.99:   4.219 ms/op
                 existUser·p0.999:  6.483 ms/op
                 existUser·p0.9999: 13.555 ms/op
                 existUser·p1.00:   14.287 ms/op

Iteration   3: 3.054 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.500 ms/op
                 existUser·p0.50:   3.019 ms/op
                 existUser·p0.90:   3.756 ms/op
                 existUser·p0.95:   3.957 ms/op
                 existUser·p0.99:   4.571 ms/op
                 existUser·p0.999:  7.210 ms/op
                 existUser·p0.9999: 15.059 ms/op
                 existUser·p1.00:   17.203 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 319035
  mean =      3.010 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1860 
    [ 1.250,  2.500) = 42359 
    [ 2.500,  3.750) = 247486 
    [ 3.750,  5.000) = 25891 
    [ 5.000,  6.250) = 880 
    [ 6.250,  7.500) = 294 
    [ 7.500,  8.750) = 67 
    [ 8.750, 10.000) = 32 
    [10.000, 11.250) = 8 
    [11.250, 12.500) = 69 
    [12.500, 13.750) = 53 
    [13.750, 15.000) = 25 
    [15.000, 16.250) = 5 
    [16.250, 17.500) = 6 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.472 ms/op
     p(50.0000) =      2.990 ms/op
     p(90.0000) =      3.703 ms/op
     p(95.0000) =      3.899 ms/op
     p(99.0000) =      4.399 ms/op
     p(99.9000) =      7.012 ms/op
     p(99.9900) =     14.296 ms/op
     p(99.9990) =     16.863 ms/op
     p(99.9999) =     17.203 ms/op
    p(100.0000) =     17.203 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.505 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.300 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.157 ±(99.9%) 0.007 ms/op
Iteration   1: 3.153 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.872 ms/op
                 getUser·p0.50:   3.113 ms/op
                 getUser·p0.90:   3.842 ms/op
                 getUser·p0.95:   4.051 ms/op
                 getUser·p0.99:   4.448 ms/op
                 getUser·p0.999:  7.892 ms/op
                 getUser·p0.9999: 13.189 ms/op
                 getUser·p1.00:   13.533 ms/op

Iteration   2: 3.174 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.420 ms/op
                 getUser·p0.50:   3.150 ms/op
                 getUser·p0.90:   3.838 ms/op
                 getUser·p0.95:   4.039 ms/op
                 getUser·p0.99:   4.637 ms/op
                 getUser·p0.999:  7.704 ms/op
                 getUser·p0.9999: 15.839 ms/op
                 getUser·p1.00:   16.171 ms/op

Iteration   3: 3.237 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.952 ms/op
                 getUser·p0.50:   3.195 ms/op
                 getUser·p0.90:   3.973 ms/op
                 getUser·p0.95:   4.149 ms/op
                 getUser·p0.99:   4.719 ms/op
                 getUser·p0.999:  7.958 ms/op
                 getUser·p0.9999: 16.340 ms/op
                 getUser·p1.00:   17.662 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 301254
  mean =      3.188 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 476 
    [ 1.250,  2.500) = 20814 
    [ 2.500,  3.750) = 235000 
    [ 3.750,  5.000) = 43318 
    [ 5.000,  6.250) = 869 
    [ 6.250,  7.500) = 372 
    [ 7.500,  8.750) = 194 
    [ 8.750, 10.000) = 24 
    [10.000, 11.250) = 27 
    [11.250, 12.500) = 19 
    [12.500, 13.750) = 45 
    [13.750, 15.000) = 31 
    [15.000, 16.250) = 56 
    [16.250, 17.500) = 4 
    [17.500, 18.750) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.420 ms/op
     p(50.0000) =      3.150 ms/op
     p(90.0000) =      3.891 ms/op
     p(95.0000) =      4.088 ms/op
     p(99.0000) =      4.579 ms/op
     p(99.9000) =      7.873 ms/op
     p(99.9900) =     15.774 ms/op
     p(99.9990) =     17.628 ms/op
     p(99.9999) =     17.662 ms/op
    p(100.0000) =     17.662 ms/op


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
# Warmup Iteration   1: 5.690 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 4.176 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.060 ±(99.9%) 0.012 ms/op
Iteration   1: 4.092 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.221 ms/op
                 listUser·p0.50:   3.940 ms/op
                 listUser·p0.90:   5.030 ms/op
                 listUser·p0.95:   5.898 ms/op
                 listUser·p0.99:   7.147 ms/op
                 listUser·p0.999:  14.268 ms/op
                 listUser·p0.9999: 16.101 ms/op
                 listUser·p1.00:   22.512 ms/op

Iteration   2: 4.021 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.268 ms/op
                 listUser·p0.50:   3.863 ms/op
                 listUser·p0.90:   4.989 ms/op
                 listUser·p0.95:   5.767 ms/op
                 listUser·p0.99:   6.996 ms/op
                 listUser·p0.999:  14.213 ms/op
                 listUser·p0.9999: 16.270 ms/op
                 listUser·p1.00:   17.170 ms/op

Iteration   3: 4.075 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.847 ms/op
                 listUser·p0.50:   3.887 ms/op
                 listUser·p0.90:   5.251 ms/op
                 listUser·p0.95:   5.923 ms/op
                 listUser·p0.99:   7.053 ms/op
                 listUser·p0.999:  16.574 ms/op
                 listUser·p0.9999: 19.802 ms/op
                 listUser·p1.00:   20.939 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 236122
  mean =      4.062 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2444 
    [ 2.500,  5.000) = 208082 
    [ 5.000,  7.500) = 24109 
    [ 7.500, 10.000) = 976 
    [10.000, 12.500) = 129 
    [12.500, 15.000) = 182 
    [15.000, 17.500) = 157 
    [17.500, 20.000) = 35 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.847 ms/op
     p(50.0000) =      3.895 ms/op
     p(90.0000) =      5.095 ms/op
     p(95.0000) =      5.874 ms/op
     p(99.0000) =      7.053 ms/op
     p(99.9000) =     14.664 ms/op
     p(99.9900) =     18.459 ms/op
     p(99.9990) =     22.357 ms/op
     p(99.9999) =     22.512 ms/op
    p(100.0000) =     22.512 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.201 ± 3.537  ops/ms
ClientGrpc.existUser                       thrpt       3  10.614 ± 0.707  ops/ms
ClientGrpc.getUser                         thrpt       3  10.175 ± 1.143  ops/ms
ClientGrpc.listUser                        thrpt       3   7.802 ± 1.055  ops/ms
ClientGrpc.createUser                       avgt       3   3.224 ± 0.762   ms/op
ClientGrpc.existUser                        avgt       3   3.040 ± 0.140   ms/op
ClientGrpc.getUser                          avgt       3   3.170 ± 0.506   ms/op
ClientGrpc.listUser                         avgt       3   4.119 ± 1.391   ms/op
ClientGrpc.createUser                     sample  304402   3.154 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.559           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.133           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.879           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.076           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.465           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.873           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.776           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          22.675           ms/op
ClientGrpc.existUser                      sample  319035   3.010 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.472           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.990           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.703           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.899           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.399           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.012           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          14.296           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.203           ms/op
ClientGrpc.getUser                        sample  301254   3.188 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.420           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.150           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.891           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.088           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.579           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.873           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          15.774           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          17.662           ms/op
ClientGrpc.listUser                       sample  236122   4.062 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.847           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.895           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.095           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.874           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.053           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.664           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          18.459           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          22.512           ms/op
