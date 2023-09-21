# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.431 ops/ms
# Warmup Iteration   2: 9.286 ops/ms
# Warmup Iteration   3: 9.779 ops/ms
Iteration   1: 10.247 ops/ms
Iteration   2: 10.235 ops/ms
Iteration   3: 10.233 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.238 ±(99.9%) 0.134 ops/ms [Average]
  (min, avg, max) = (10.233, 10.238, 10.247), stdev = 0.007
  CI (99.9%): [10.104, 10.372] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 7.712 ops/ms
# Warmup Iteration   2: 10.553 ops/ms
# Warmup Iteration   3: 10.749 ops/ms
Iteration   1: 10.496 ops/ms
Iteration   2: 10.682 ops/ms
Iteration   3: 10.746 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.641 ±(99.9%) 2.364 ops/ms [Average]
  (min, avg, max) = (10.496, 10.641, 10.746), stdev = 0.130
  CI (99.9%): [8.277, 13.005] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 7.116 ops/ms
# Warmup Iteration   2: 10.070 ops/ms
# Warmup Iteration   3: 10.192 ops/ms
Iteration   1: 10.317 ops/ms
Iteration   2: 10.168 ops/ms
Iteration   3: 10.422 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.303 ±(99.9%) 2.327 ops/ms [Average]
  (min, avg, max) = (10.168, 10.303, 10.422), stdev = 0.128
  CI (99.9%): [7.976, 12.629] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 5.980 ops/ms
# Warmup Iteration   2: 7.910 ops/ms
# Warmup Iteration   3: 8.217 ops/ms
Iteration   1: 8.228 ops/ms
Iteration   2: 8.184 ops/ms
Iteration   3: 8.192 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.202 ±(99.9%) 0.427 ops/ms [Average]
  (min, avg, max) = (8.184, 8.202, 8.228), stdev = 0.023
  CI (99.9%): [7.775, 8.629] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.337 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.197 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.189 ±(99.9%) 0.008 ms/op
Iteration   1: 3.146 ±(99.9%) 0.002 ms/op
Iteration   2: 3.085 ±(99.9%) 0.003 ms/op
Iteration   3: 3.151 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.128 ±(99.9%) 0.675 ms/op [Average]
  (min, avg, max) = (3.085, 3.128, 3.151), stdev = 0.037
  CI (99.9%): [2.453, 3.802] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 3.936 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.030 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.000 ±(99.9%) 0.003 ms/op
Iteration   1: 2.955 ±(99.9%) 0.002 ms/op
Iteration   2: 2.967 ±(99.9%) 0.002 ms/op
Iteration   3: 2.985 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.969 ±(99.9%) 0.271 ms/op [Average]
  (min, avg, max) = (2.955, 2.969, 2.985), stdev = 0.015
  CI (99.9%): [2.699, 3.240] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.059 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.174 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.151 ±(99.9%) 0.002 ms/op
Iteration   1: 3.197 ±(99.9%) 0.002 ms/op
Iteration   2: 3.075 ±(99.9%) 0.003 ms/op
Iteration   3: 3.159 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.144 ±(99.9%) 1.143 ms/op [Average]
  (min, avg, max) = (3.075, 3.144, 3.197), stdev = 0.063
  CI (99.9%): [2.001, 4.286] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 5.251 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 4.052 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 3.891 ±(99.9%) 0.008 ms/op
Iteration   1: 3.949 ±(99.9%) 0.021 ms/op
Iteration   2: 3.920 ±(99.9%) 0.022 ms/op
Iteration   3: 3.921 ±(99.9%) 0.023 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.930 ±(99.9%) 0.302 ms/op [Average]
  (min, avg, max) = (3.920, 3.930, 3.949), stdev = 0.017
  CI (99.9%): [3.628, 4.232] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 4.102 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.234 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.169 ±(99.9%) 0.007 ms/op
Iteration   1: 3.114 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.635 ms/op
                 createUser·p0.50:   3.068 ms/op
                 createUser·p0.90:   3.600 ms/op
                 createUser·p0.95:   3.801 ms/op
                 createUser·p0.99:   4.448 ms/op
                 createUser·p0.999:  8.230 ms/op
                 createUser·p0.9999: 17.162 ms/op
                 createUser·p1.00:   17.433 ms/op

Iteration   2: 3.132 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.738 ms/op
                 createUser·p0.50:   3.088 ms/op
                 createUser·p0.90:   3.752 ms/op
                 createUser·p0.95:   3.916 ms/op
                 createUser·p0.99:   4.432 ms/op
                 createUser·p0.999:  7.019 ms/op
                 createUser·p0.9999: 17.025 ms/op
                 createUser·p1.00:   17.203 ms/op

Iteration   3: 3.130 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.726 ms/op
                 createUser·p0.50:   3.088 ms/op
                 createUser·p0.90:   3.609 ms/op
                 createUser·p0.95:   3.711 ms/op
                 createUser·p0.99:   4.121 ms/op
                 createUser·p0.999:  10.813 ms/op
                 createUser·p0.9999: 23.396 ms/op
                 createUser·p1.00:   23.429 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 307104
  mean =      3.125 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9221 
    [ 2.500,  5.000) = 296232 
    [ 5.000,  7.500) = 1229 
    [ 7.500, 10.000) = 170 
    [10.000, 12.500) = 28 
    [12.500, 15.000) = 36 
    [15.000, 17.500) = 150 
    [17.500, 20.000) = 6 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.635 ms/op
     p(50.0000) =      3.080 ms/op
     p(90.0000) =      3.645 ms/op
     p(95.0000) =      3.817 ms/op
     p(99.0000) =      4.366 ms/op
     p(99.9000) =      8.946 ms/op
     p(99.9900) =     22.259 ms/op
     p(99.9990) =     23.429 ms/op
     p(99.9999) =     23.429 ms/op
    p(100.0000) =     23.429 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 3.850 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.029 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.048 ±(99.9%) 0.005 ms/op
Iteration   1: 3.004 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.801 ms/op
                 existUser·p0.50:   2.957 ms/op
                 existUser·p0.90:   3.572 ms/op
                 existUser·p0.95:   3.772 ms/op
                 existUser·p0.99:   4.579 ms/op
                 existUser·p0.999:  7.131 ms/op
                 existUser·p0.9999: 12.611 ms/op
                 existUser·p1.00:   13.042 ms/op

Iteration   2: 2.987 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.706 ms/op
                 existUser·p0.50:   2.961 ms/op
                 existUser·p0.90:   3.584 ms/op
                 existUser·p0.95:   3.785 ms/op
                 existUser·p0.99:   4.407 ms/op
                 existUser·p0.999:  10.114 ms/op
                 existUser·p0.9999: 14.820 ms/op
                 existUser·p1.00:   15.188 ms/op

Iteration   3: 3.068 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.894 ms/op
                 existUser·p0.50:   3.027 ms/op
                 existUser·p0.90:   3.584 ms/op
                 existUser·p0.95:   3.703 ms/op
                 existUser·p0.99:   4.366 ms/op
                 existUser·p0.999:  6.456 ms/op
                 existUser·p0.9999: 14.011 ms/op
                 existUser·p1.00:   14.418 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 318123
  mean =      3.019 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1762 
    [ 1.250,  2.500) = 18858 
    [ 2.500,  3.750) = 281625 
    [ 3.750,  5.000) = 14395 
    [ 5.000,  6.250) = 918 
    [ 6.250,  7.500) = 289 
    [ 7.500,  8.750) = 20 
    [ 8.750, 10.000) = 11 
    [10.000, 11.250) = 70 
    [11.250, 12.500) = 34 
    [12.500, 13.750) = 68 
    [13.750, 15.000) = 68 
    [15.000, 16.250) = 5 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.706 ms/op
     p(50.0000) =      2.978 ms/op
     p(90.0000) =      3.580 ms/op
     p(95.0000) =      3.748 ms/op
     p(99.0000) =      4.463 ms/op
     p(99.9000) =      6.980 ms/op
     p(99.9900) =     14.192 ms/op
     p(99.9990) =     15.114 ms/op
     p(99.9999) =     15.188 ms/op
    p(100.0000) =     15.188 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.082 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.276 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.115 ±(99.9%) 0.007 ms/op
Iteration   1: 3.148 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.686 ms/op
                 getUser·p0.50:   3.097 ms/op
                 getUser·p0.90:   3.711 ms/op
                 getUser·p0.95:   3.912 ms/op
                 getUser·p0.99:   4.461 ms/op
                 getUser·p0.999:  12.663 ms/op
                 getUser·p0.9999: 19.946 ms/op
                 getUser·p1.00:   20.578 ms/op

Iteration   2: 3.156 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.584 ms/op
                 getUser·p0.50:   3.121 ms/op
                 getUser·p0.90:   3.678 ms/op
                 getUser·p0.95:   3.822 ms/op
                 getUser·p0.99:   4.530 ms/op
                 getUser·p0.999:  8.602 ms/op
                 getUser·p0.9999: 20.306 ms/op
                 getUser·p1.00:   22.020 ms/op

Iteration   3: 3.161 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.867 ms/op
                 getUser·p0.50:   3.117 ms/op
                 getUser·p0.90:   3.686 ms/op
                 getUser·p0.95:   3.813 ms/op
                 getUser·p0.99:   4.076 ms/op
                 getUser·p0.999:  6.929 ms/op
                 getUser·p0.9999: 22.737 ms/op
                 getUser·p1.00:   23.200 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 304179
  mean =      3.155 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6478 
    [ 2.500,  5.000) = 296018 
    [ 5.000,  7.500) = 1213 
    [ 7.500, 10.000) = 266 
    [10.000, 12.500) = 7 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 37 
    [17.500, 20.000) = 77 
    [20.000, 22.500) = 65 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.584 ms/op
     p(50.0000) =      3.113 ms/op
     p(90.0000) =      3.690 ms/op
     p(95.0000) =      3.842 ms/op
     p(99.0000) =      4.309 ms/op
     p(99.9000) =      8.684 ms/op
     p(99.9900) =     22.039 ms/op
     p(99.9990) =     23.066 ms/op
     p(99.9999) =     23.200 ms/op
    p(100.0000) =     23.200 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 5.364 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 4.007 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.917 ±(99.9%) 0.010 ms/op
Iteration   1: 3.860 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.174 ms/op
                 listUser·p0.50:   3.719 ms/op
                 listUser·p0.90:   4.833 ms/op
                 listUser·p0.95:   5.800 ms/op
                 listUser·p0.99:   6.717 ms/op
                 listUser·p0.999:  11.799 ms/op
                 listUser·p0.9999: 13.514 ms/op
                 listUser·p1.00:   14.041 ms/op

Iteration   2: 3.767 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.165 ms/op
                 listUser·p0.50:   3.707 ms/op
                 listUser·p0.90:   4.202 ms/op
                 listUser·p0.95:   4.686 ms/op
                 listUser·p0.99:   6.414 ms/op
                 listUser·p0.999:  12.648 ms/op
                 listUser·p0.9999: 16.474 ms/op
                 listUser·p1.00:   16.876 ms/op

Iteration   3: 3.923 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.000 ms/op
                 listUser·p0.50:   3.834 ms/op
                 listUser·p0.90:   4.375 ms/op
                 listUser·p0.95:   5.390 ms/op
                 listUser·p0.99:   6.578 ms/op
                 listUser·p0.999:  13.573 ms/op
                 listUser·p0.9999: 19.988 ms/op
                 listUser·p1.00:   21.987 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 249328
  mean =      3.849 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3681 
    [ 2.500,  5.000) = 229634 
    [ 5.000,  7.500) = 15173 
    [ 7.500, 10.000) = 436 
    [10.000, 12.500) = 144 
    [12.500, 15.000) = 182 
    [15.000, 17.500) = 43 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.000 ms/op
     p(50.0000) =      3.756 ms/op
     p(90.0000) =      4.383 ms/op
     p(95.0000) =      5.431 ms/op
     p(99.0000) =      6.578 ms/op
     p(99.9000) =     12.567 ms/op
     p(99.9900) =     19.565 ms/op
     p(99.9990) =     21.561 ms/op
     p(99.9999) =     21.987 ms/op
    p(100.0000) =     21.987 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.238 ± 0.134  ops/ms
ClientGrpc.existUser                       thrpt       3  10.641 ± 2.364  ops/ms
ClientGrpc.getUser                         thrpt       3  10.303 ± 2.327  ops/ms
ClientGrpc.listUser                        thrpt       3   8.202 ± 0.427  ops/ms
ClientGrpc.createUser                       avgt       3   3.128 ± 0.675   ms/op
ClientGrpc.existUser                        avgt       3   2.969 ± 0.271   ms/op
ClientGrpc.getUser                          avgt       3   3.144 ± 1.143   ms/op
ClientGrpc.listUser                         avgt       3   3.930 ± 0.302   ms/op
ClientGrpc.createUser                     sample  307104   3.125 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.635           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.080           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.645           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.817           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.366           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.946           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          22.259           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          23.429           ms/op
ClientGrpc.existUser                      sample  318123   3.019 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.706           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.978           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.580           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.748           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.463           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.980           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          14.192           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          15.188           ms/op
ClientGrpc.getUser                        sample  304179   3.155 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.584           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.113           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.690           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.842           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.309           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.684           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          22.039           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          23.200           ms/op
ClientGrpc.listUser                       sample  249328   3.849 ± 0.005   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.000           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.756           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.383           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.431           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.578           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          12.567           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          19.565           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          21.987           ms/op
