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
# Warmup Iteration   1: 2.253 ops/ms
# Warmup Iteration   2: 5.659 ops/ms
# Warmup Iteration   3: 7.432 ops/ms
Iteration   1: 7.392 ops/ms
Iteration   2: 7.342 ops/ms
Iteration   3: 7.761 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.498 ±(99.9%) 4.177 ops/ms [Average]
  (min, avg, max) = (7.342, 7.498, 7.761), stdev = 0.229
  CI (99.9%): [3.321, 11.676] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:04
# Fork: 1 of 1
# Warmup Iteration   1: 5.014 ops/ms
# Warmup Iteration   2: 7.553 ops/ms
# Warmup Iteration   3: 8.237 ops/ms
Iteration   1: 8.080 ops/ms
Iteration   2: 8.467 ops/ms
Iteration   3: 8.144 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.230 ±(99.9%) 3.779 ops/ms [Average]
  (min, avg, max) = (8.080, 8.230, 8.467), stdev = 0.207
  CI (99.9%): [4.451, 12.010] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:58
# Fork: 1 of 1
# Warmup Iteration   1: 4.661 ops/ms
# Warmup Iteration   2: 7.138 ops/ms
# Warmup Iteration   3: 7.033 ops/ms
Iteration   1: 7.521 ops/ms
Iteration   2: 7.709 ops/ms
Iteration   3: 7.559 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.596 ±(99.9%) 1.819 ops/ms [Average]
  (min, avg, max) = (7.521, 7.596, 7.709), stdev = 0.100
  CI (99.9%): [5.778, 9.415] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 3.966 ops/ms
# Warmup Iteration   2: 5.431 ops/ms
# Warmup Iteration   3: 5.699 ops/ms
Iteration   1: 6.086 ops/ms
Iteration   2: 5.890 ops/ms
Iteration   3: 5.987 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.988 ±(99.9%) 1.784 ops/ms [Average]
  (min, avg, max) = (5.890, 5.988, 6.086), stdev = 0.098
  CI (99.9%): [4.204, 7.772] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 6.681 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 4.500 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.259 ±(99.9%) 0.014 ms/op
Iteration   1: 4.099 ±(99.9%) 0.005 ms/op
Iteration   2: 4.158 ±(99.9%) 0.003 ms/op
Iteration   3: 4.239 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.165 ±(99.9%) 1.281 ms/op [Average]
  (min, avg, max) = (4.099, 4.165, 4.239), stdev = 0.070
  CI (99.9%): [2.885, 5.446] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 5.988 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 4.304 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.010 ±(99.9%) 0.004 ms/op
Iteration   1: 3.993 ±(99.9%) 0.003 ms/op
Iteration   2: 3.922 ±(99.9%) 0.003 ms/op
Iteration   3: 3.789 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.901 ±(99.9%) 1.889 ms/op [Average]
  (min, avg, max) = (3.789, 3.901, 3.993), stdev = 0.104
  CI (99.9%): [2.012, 5.790] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 6.382 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 4.361 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 4.279 ±(99.9%) 0.012 ms/op
Iteration   1: 4.173 ±(99.9%) 0.004 ms/op
Iteration   2: 4.119 ±(99.9%) 0.003 ms/op
Iteration   3: 4.067 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.120 ±(99.9%) 0.968 ms/op [Average]
  (min, avg, max) = (4.067, 4.120, 4.173), stdev = 0.053
  CI (99.9%): [3.152, 5.088] (assumes normal distribution)


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
# Warmup Iteration   1: 8.556 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 5.761 ±(99.9%) 0.038 ms/op
# Warmup Iteration   3: 5.548 ±(99.9%) 0.017 ms/op
Iteration   1: 5.481 ±(99.9%) 0.030 ms/op
Iteration   2: 5.426 ±(99.9%) 0.041 ms/op
Iteration   3: 5.617 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.508 ±(99.9%) 1.795 ms/op [Average]
  (min, avg, max) = (5.426, 5.508, 5.617), stdev = 0.098
  CI (99.9%): [3.712, 7.303] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 6.108 ±(99.9%) 0.073 ms/op
# Warmup Iteration   2: 4.501 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.318 ±(99.9%) 0.014 ms/op
Iteration   1: 4.288 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.376 ms/op
                 createUser·p0.50:   4.137 ms/op
                 createUser·p0.90:   5.439 ms/op
                 createUser·p0.95:   5.939 ms/op
                 createUser·p0.99:   7.799 ms/op
                 createUser·p0.999:  12.861 ms/op
                 createUser·p0.9999: 15.331 ms/op
                 createUser·p1.00:   15.991 ms/op

Iteration   2: 4.227 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   0.791 ms/op
                 createUser·p0.50:   4.055 ms/op
                 createUser·p0.90:   5.308 ms/op
                 createUser·p0.95:   5.890 ms/op
                 createUser·p0.99:   8.356 ms/op
                 createUser·p0.999:  15.779 ms/op
                 createUser·p0.9999: 23.658 ms/op
                 createUser·p1.00:   24.183 ms/op

Iteration   3: 4.298 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.137 ms/op
                 createUser·p0.50:   4.153 ms/op
                 createUser·p0.90:   5.480 ms/op
                 createUser·p0.95:   6.038 ms/op
                 createUser·p0.99:   8.118 ms/op
                 createUser·p0.999:  13.840 ms/op
                 createUser·p0.9999: 33.292 ms/op
                 createUser·p1.00:   33.358 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 224725
  mean =      4.271 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3405 
    [ 2.500,  5.000) = 182409 
    [ 5.000,  7.500) = 35657 
    [ 7.500, 10.000) = 2483 
    [10.000, 12.500) = 396 
    [12.500, 15.000) = 185 
    [15.000, 17.500) = 113 
    [17.500, 20.000) = 13 
    [20.000, 22.500) = 16 
    [22.500, 25.000) = 16 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 1 
    [30.000, 32.500) = 11 
    [32.500, 35.000) = 20 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.791 ms/op
     p(50.0000) =      4.112 ms/op
     p(90.0000) =      5.415 ms/op
     p(95.0000) =      5.964 ms/op
     p(99.0000) =      8.086 ms/op
     p(99.9000) =     14.504 ms/op
     p(99.9900) =     32.311 ms/op
     p(99.9990) =     33.358 ms/op
     p(99.9999) =     33.358 ms/op
    p(100.0000) =     33.358 ms/op


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
# Warmup Iteration   1: 5.731 ±(99.9%) 0.063 ms/op
# Warmup Iteration   2: 4.227 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.923 ±(99.9%) 0.011 ms/op
Iteration   1: 3.899 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.124 ms/op
                 existUser·p0.50:   3.772 ms/op
                 existUser·p0.90:   4.956 ms/op
                 existUser·p0.95:   5.407 ms/op
                 existUser·p0.99:   7.143 ms/op
                 existUser·p0.999:  10.404 ms/op
                 existUser·p0.9999: 16.053 ms/op
                 existUser·p1.00:   16.876 ms/op

Iteration   2: 4.037 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.935 ms/op
                 existUser·p0.50:   3.912 ms/op
                 existUser·p0.90:   4.973 ms/op
                 existUser·p0.95:   5.480 ms/op
                 existUser·p0.99:   7.225 ms/op
                 existUser·p0.999:  12.882 ms/op
                 existUser·p0.9999: 18.285 ms/op
                 existUser·p1.00:   19.825 ms/op

Iteration   3: 3.843 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.716 ms/op
                 existUser·p0.50:   3.740 ms/op
                 existUser·p0.90:   4.825 ms/op
                 existUser·p0.95:   5.308 ms/op
                 existUser·p0.99:   6.791 ms/op
                 existUser·p0.999:  11.567 ms/op
                 existUser·p0.9999: 20.207 ms/op
                 existUser·p1.00:   21.168 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 244574
  mean =      3.924 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6837 
    [ 2.500,  5.000) = 216011 
    [ 5.000,  7.500) = 19953 
    [ 7.500, 10.000) = 1268 
    [10.000, 12.500) = 299 
    [12.500, 15.000) = 92 
    [15.000, 17.500) = 47 
    [17.500, 20.000) = 54 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.716 ms/op
     p(50.0000) =      3.809 ms/op
     p(90.0000) =      4.923 ms/op
     p(95.0000) =      5.399 ms/op
     p(99.0000) =      7.070 ms/op
     p(99.9000) =     11.567 ms/op
     p(99.9900) =     19.235 ms/op
     p(99.9990) =     20.866 ms/op
     p(99.9999) =     21.168 ms/op
    p(100.0000) =     21.168 ms/op


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
# Warmup Iteration   1: 6.440 ±(99.9%) 0.074 ms/op
# Warmup Iteration   2: 4.641 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.247 ±(99.9%) 0.013 ms/op
Iteration   1: 4.222 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   0.955 ms/op
                 getUser·p0.50:   4.084 ms/op
                 getUser·p0.90:   5.325 ms/op
                 getUser·p0.95:   5.882 ms/op
                 getUser·p0.99:   7.823 ms/op
                 getUser·p0.999:  12.883 ms/op
                 getUser·p0.9999: 21.509 ms/op
                 getUser·p1.00:   22.020 ms/op

Iteration   2: 4.165 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.046 ms/op
                 getUser·p0.50:   4.063 ms/op
                 getUser·p0.90:   5.194 ms/op
                 getUser·p0.95:   5.726 ms/op
                 getUser·p0.99:   7.422 ms/op
                 getUser·p0.999:  13.523 ms/op
                 getUser·p0.9999: 34.689 ms/op
                 getUser·p1.00:   36.700 ms/op

Iteration   3: 4.194 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   0.517 ms/op
                 getUser·p0.50:   4.071 ms/op
                 getUser·p0.90:   5.226 ms/op
                 getUser·p0.95:   5.718 ms/op
                 getUser·p0.99:   7.455 ms/op
                 getUser·p0.999:  15.284 ms/op
                 getUser·p0.9999: 28.871 ms/op
                 getUser·p1.00:   29.458 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 229093
  mean =      4.194 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5410 
    [ 2.500,  5.000) = 190532 
    [ 5.000,  7.500) = 30756 
    [ 7.500, 10.000) = 1699 
    [10.000, 12.500) = 370 
    [12.500, 15.000) = 111 
    [15.000, 17.500) = 75 
    [17.500, 20.000) = 20 
    [20.000, 22.500) = 47 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 3 
    [27.500, 30.000) = 30 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 29 
    [35.000, 37.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.517 ms/op
     p(50.0000) =      4.071 ms/op
     p(90.0000) =      5.251 ms/op
     p(95.0000) =      5.784 ms/op
     p(99.0000) =      7.569 ms/op
     p(99.9000) =     13.943 ms/op
     p(99.9900) =     32.974 ms/op
     p(99.9990) =     36.482 ms/op
     p(99.9999) =     36.700 ms/op
    p(100.0000) =     36.700 ms/op


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
# Warmup Iteration   1: 8.010 ±(99.9%) 0.100 ms/op
# Warmup Iteration   2: 5.832 ±(99.9%) 0.030 ms/op
# Warmup Iteration   3: 5.542 ±(99.9%) 0.024 ms/op
Iteration   1: 5.542 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   1.845 ms/op
                 listUser·p0.50:   5.194 ms/op
                 listUser·p0.90:   7.627 ms/op
                 listUser·p0.95:   8.684 ms/op
                 listUser·p0.99:   11.159 ms/op
                 listUser·p0.999:  17.503 ms/op
                 listUser·p0.9999: 29.400 ms/op
                 listUser·p1.00:   29.622 ms/op

Iteration   2: 5.428 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   1.075 ms/op
                 listUser·p0.50:   5.071 ms/op
                 listUser·p0.90:   7.463 ms/op
                 listUser·p0.95:   8.536 ms/op
                 listUser·p0.99:   10.977 ms/op
                 listUser·p0.999:  20.584 ms/op
                 listUser·p0.9999: 26.625 ms/op
                 listUser·p1.00:   27.853 ms/op

Iteration   3: 5.302 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   1.278 ms/op
                 listUser·p0.50:   4.981 ms/op
                 listUser·p0.90:   7.217 ms/op
                 listUser·p0.95:   8.176 ms/op
                 listUser·p0.99:   10.584 ms/op
                 listUser·p0.999:  23.276 ms/op
                 listUser·p0.9999: 36.628 ms/op
                 listUser·p1.00:   36.962 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 176968
  mean =      5.422 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 367 
    [ 2.500,  5.000) = 83131 
    [ 5.000,  7.500) = 76437 
    [ 7.500, 10.000) = 13969 
    [10.000, 12.500) = 2314 
    [12.500, 15.000) = 363 
    [15.000, 17.500) = 143 
    [17.500, 20.000) = 47 
    [20.000, 22.500) = 54 
    [22.500, 25.000) = 35 
    [25.000, 27.500) = 30 
    [27.500, 30.000) = 44 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 19 
    [35.000, 37.500) = 13 

  Percentiles, ms/op:
      p(0.0000) =      1.075 ms/op
     p(50.0000) =      5.079 ms/op
     p(90.0000) =      7.438 ms/op
     p(95.0000) =      8.454 ms/op
     p(99.0000) =     10.912 ms/op
     p(99.9000) =     21.004 ms/op
     p(99.9900) =     33.882 ms/op
     p(99.9990) =     36.912 ms/op
     p(99.9999) =     36.962 ms/op
    p(100.0000) =     36.962 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.498 ± 4.177  ops/ms
ClientGrpc.existUser                       thrpt       3   8.230 ± 3.779  ops/ms
ClientGrpc.getUser                         thrpt       3   7.596 ± 1.819  ops/ms
ClientGrpc.listUser                        thrpt       3   5.988 ± 1.784  ops/ms
ClientGrpc.createUser                       avgt       3   4.165 ± 1.281   ms/op
ClientGrpc.existUser                        avgt       3   3.901 ± 1.889   ms/op
ClientGrpc.getUser                          avgt       3   4.120 ± 0.968   ms/op
ClientGrpc.listUser                         avgt       3   5.508 ± 1.795   ms/op
ClientGrpc.createUser                     sample  224725   4.271 ± 0.008   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.791           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.112           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.415           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.964           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           8.086           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          14.504           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          32.311           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          33.358           ms/op
ClientGrpc.existUser                      sample  244574   3.924 ± 0.006   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.716           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.809           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.923           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.399           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           7.070           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          11.567           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.235           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          21.168           ms/op
ClientGrpc.getUser                        sample  229093   4.194 ± 0.008   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.517           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.071           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.251           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.784           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.569           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          13.943           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          32.974           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          36.700           ms/op
ClientGrpc.listUser                       sample  176968   5.422 ± 0.013   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.075           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.079           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.438           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           8.454           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          10.912           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          21.004           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          33.882           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          36.962           ms/op
