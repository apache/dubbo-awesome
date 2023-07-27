# JMH version: 1.21
# VM version: JDK 11.0.19, OpenJDK 64-Bit Server VM, 11.0.19+7
# VM invoker: /usr/lib/jvm/temurin-11-jdk-amd64/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.842 ops/ms
# Warmup Iteration   2: 6.610 ops/ms
# Warmup Iteration   3: 8.456 ops/ms
Iteration   1: 9.233 ops/ms
Iteration   2: 9.393 ops/ms
Iteration   3: 9.502 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  9.376 ±(99.9%) 2.461 ops/ms [Average]
  (min, avg, max) = (9.233, 9.376, 9.502), stdev = 0.135
  CI (99.9%): [6.915, 11.837] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 11.0.19, OpenJDK 64-Bit Server VM, 11.0.19+7
# VM invoker: /usr/lib/jvm/temurin-11-jdk-amd64/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 6.048 ops/ms
# Warmup Iteration   2: 9.110 ops/ms
# Warmup Iteration   3: 9.235 ops/ms
Iteration   1: 9.520 ops/ms
Iteration   2: 9.570 ops/ms
Iteration   3: 9.661 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.584 ±(99.9%) 1.306 ops/ms [Average]
  (min, avg, max) = (9.520, 9.584, 9.661), stdev = 0.072
  CI (99.9%): [8.278, 10.890] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 11.0.19, OpenJDK 64-Bit Server VM, 11.0.19+7
# VM invoker: /usr/lib/jvm/temurin-11-jdk-amd64/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 5.288 ops/ms
# Warmup Iteration   2: 8.385 ops/ms
# Warmup Iteration   3: 9.117 ops/ms
Iteration   1: 9.249 ops/ms
Iteration   2: 9.220 ops/ms
Iteration   3: 9.278 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  9.249 ±(99.9%) 0.529 ops/ms [Average]
  (min, avg, max) = (9.220, 9.249, 9.278), stdev = 0.029
  CI (99.9%): [8.721, 9.778] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 11.0.19, OpenJDK 64-Bit Server VM, 11.0.19+7
# VM invoker: /usr/lib/jvm/temurin-11-jdk-amd64/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 4.432 ops/ms
# Warmup Iteration   2: 6.596 ops/ms
# Warmup Iteration   3: 7.248 ops/ms
Iteration   1: 7.653 ops/ms
Iteration   2: 7.453 ops/ms
Iteration   3: 7.553 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.553 ±(99.9%) 1.827 ops/ms [Average]
  (min, avg, max) = (7.453, 7.553, 7.653), stdev = 0.100
  CI (99.9%): [5.726, 9.380] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 11.0.19, OpenJDK 64-Bit Server VM, 11.0.19+7
# VM invoker: /usr/lib/jvm/temurin-11-jdk-amd64/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 5.703 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.778 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.531 ±(99.9%) 0.011 ms/op
Iteration   1: 3.408 ±(99.9%) 0.008 ms/op
Iteration   2: 3.390 ±(99.9%) 0.006 ms/op
Iteration   3: 3.398 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.399 ±(99.9%) 0.172 ms/op [Average]
  (min, avg, max) = (3.390, 3.399, 3.408), stdev = 0.009
  CI (99.9%): [3.227, 3.570] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 11.0.19, OpenJDK 64-Bit Server VM, 11.0.19+7
# VM invoker: /usr/lib/jvm/temurin-11-jdk-amd64/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.779 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.563 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.161 ±(99.9%) 0.007 ms/op
Iteration   1: 3.219 ±(99.9%) 0.008 ms/op
Iteration   2: 3.177 ±(99.9%) 0.005 ms/op
Iteration   3: 3.126 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.174 ±(99.9%) 0.858 ms/op [Average]
  (min, avg, max) = (3.126, 3.174, 3.219), stdev = 0.047
  CI (99.9%): [2.316, 4.032] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 11.0.19, OpenJDK 64-Bit Server VM, 11.0.19+7
# VM invoker: /usr/lib/jvm/temurin-11-jdk-amd64/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 5.356 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.609 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.438 ±(99.9%) 0.010 ms/op
Iteration   1: 3.510 ±(99.9%) 0.009 ms/op
Iteration   2: 3.446 ±(99.9%) 0.008 ms/op
Iteration   3: 3.420 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.459 ±(99.9%) 0.847 ms/op [Average]
  (min, avg, max) = (3.420, 3.459, 3.510), stdev = 0.046
  CI (99.9%): [2.611, 4.306] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 11.0.19, OpenJDK 64-Bit Server VM, 11.0.19+7
# VM invoker: /usr/lib/jvm/temurin-11-jdk-amd64/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 6.309 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 4.647 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.320 ±(99.9%) 0.012 ms/op
Iteration   1: 4.279 ±(99.9%) 0.011 ms/op
Iteration   2: 4.230 ±(99.9%) 0.013 ms/op
Iteration   3: 4.163 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.224 ±(99.9%) 1.065 ms/op [Average]
  (min, avg, max) = (4.163, 4.224, 4.279), stdev = 0.058
  CI (99.9%): [3.159, 5.289] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 11.0.19, OpenJDK 64-Bit Server VM, 11.0.19+7
# VM invoker: /usr/lib/jvm/temurin-11-jdk-amd64/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 5.248 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 3.952 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.492 ±(99.9%) 0.010 ms/op
Iteration   1: 3.387 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.777 ms/op
                 createUser·p0.50:   3.293 ms/op
                 createUser·p0.90:   4.219 ms/op
                 createUser·p0.95:   4.563 ms/op
                 createUser·p0.99:   5.987 ms/op
                 createUser·p0.999:  10.006 ms/op
                 createUser·p0.9999: 16.704 ms/op
                 createUser·p1.00:   17.007 ms/op

Iteration   2: 3.368 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.969 ms/op
                 createUser·p0.50:   3.269 ms/op
                 createUser·p0.90:   4.194 ms/op
                 createUser·p0.95:   4.571 ms/op
                 createUser·p0.99:   6.038 ms/op
                 createUser·p0.999:  16.684 ms/op
                 createUser·p0.9999: 23.151 ms/op
                 createUser·p1.00:   23.527 ms/op

Iteration   3: 3.377 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.617 ms/op
                 createUser·p0.50:   3.305 ms/op
                 createUser·p0.90:   4.211 ms/op
                 createUser·p0.95:   4.547 ms/op
                 createUser·p0.99:   5.677 ms/op
                 createUser·p0.999:  8.765 ms/op
                 createUser·p0.9999: 16.606 ms/op
                 createUser·p1.00:   16.843 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 284103
  mean =      3.377 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21190 
    [ 2.500,  5.000) = 255934 
    [ 5.000,  7.500) = 5778 
    [ 7.500, 10.000) = 761 
    [10.000, 12.500) = 247 
    [12.500, 15.000) = 40 
    [15.000, 17.500) = 96 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.617 ms/op
     p(50.0000) =      3.289 ms/op
     p(90.0000) =      4.211 ms/op
     p(95.0000) =      4.563 ms/op
     p(99.0000) =      5.882 ms/op
     p(99.9000) =     11.254 ms/op
     p(99.9900) =     22.741 ms/op
     p(99.9990) =     23.336 ms/op
     p(99.9999) =     23.527 ms/op
    p(100.0000) =     23.527 ms/op


# JMH version: 1.21
# VM version: JDK 11.0.19, OpenJDK 64-Bit Server VM, 11.0.19+7
# VM invoker: /usr/lib/jvm/temurin-11-jdk-amd64/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 5.028 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.660 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.411 ±(99.9%) 0.010 ms/op
Iteration   1: 3.345 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.645 ms/op
                 existUser·p0.50:   3.252 ms/op
                 existUser·p0.90:   4.137 ms/op
                 existUser·p0.95:   4.502 ms/op
                 existUser·p0.99:   6.431 ms/op
                 existUser·p0.999:  11.000 ms/op
                 existUser·p0.9999: 15.479 ms/op
                 existUser·p1.00:   16.024 ms/op

Iteration   2: 3.226 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.571 ms/op
                 existUser·p0.50:   3.174 ms/op
                 existUser·p0.90:   4.162 ms/op
                 existUser·p0.95:   4.530 ms/op
                 existUser·p0.99:   5.874 ms/op
                 existUser·p0.999:  11.961 ms/op
                 existUser·p0.9999: 22.842 ms/op
                 existUser·p1.00:   23.429 ms/op

Iteration   3: 3.289 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.904 ms/op
                 existUser·p0.50:   3.207 ms/op
                 existUser·p0.90:   4.129 ms/op
                 existUser·p0.95:   4.481 ms/op
                 existUser·p0.99:   5.947 ms/op
                 existUser·p0.999:  13.087 ms/op
                 existUser·p0.9999: 34.687 ms/op
                 existUser·p1.00:   36.438 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 291978
  mean =      3.286 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 34275 
    [ 2.500,  5.000) = 250719 
    [ 5.000,  7.500) = 5482 
    [ 7.500, 10.000) = 937 
    [10.000, 12.500) = 335 
    [12.500, 15.000) = 106 
    [15.000, 17.500) = 27 
    [17.500, 20.000) = 21 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 20 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 4 
    [32.500, 35.000) = 24 
    [35.000, 37.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.571 ms/op
     p(50.0000) =      3.211 ms/op
     p(90.0000) =      4.141 ms/op
     p(95.0000) =      4.506 ms/op
     p(99.0000) =      6.128 ms/op
     p(99.9000) =     12.091 ms/op
     p(99.9900) =     31.884 ms/op
     p(99.9990) =     35.133 ms/op
     p(99.9999) =     36.438 ms/op
    p(100.0000) =     36.438 ms/op


# JMH version: 1.21
# VM version: JDK 11.0.19, OpenJDK 64-Bit Server VM, 11.0.19+7
# VM invoker: /usr/lib/jvm/temurin-11-jdk-amd64/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 5.759 ±(99.9%) 0.067 ms/op
# Warmup Iteration   2: 3.810 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.524 ±(99.9%) 0.011 ms/op
Iteration   1: 3.449 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.964 ms/op
                 getUser·p0.50:   3.346 ms/op
                 getUser·p0.90:   4.317 ms/op
                 getUser·p0.95:   4.710 ms/op
                 getUser·p0.99:   6.615 ms/op
                 getUser·p0.999:  13.108 ms/op
                 getUser·p0.9999: 16.412 ms/op
                 getUser·p1.00:   17.138 ms/op

Iteration   2: 3.430 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.916 ms/op
                 getUser·p0.50:   3.351 ms/op
                 getUser·p0.90:   4.252 ms/op
                 getUser·p0.95:   4.579 ms/op
                 getUser·p0.99:   5.816 ms/op
                 getUser·p0.999:  8.908 ms/op
                 getUser·p0.9999: 16.090 ms/op
                 getUser·p1.00:   16.777 ms/op

Iteration   3: 3.386 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.071 ms/op
                 getUser·p0.50:   3.301 ms/op
                 getUser·p0.90:   4.174 ms/op
                 getUser·p0.95:   4.530 ms/op
                 getUser·p0.99:   5.986 ms/op
                 getUser·p0.999:  10.109 ms/op
                 getUser·p0.9999: 21.529 ms/op
                 getUser·p1.00:   23.429 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 280350
  mean =      3.421 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19534 
    [ 2.500,  5.000) = 253238 
    [ 5.000,  7.500) = 6276 
    [ 7.500, 10.000) = 959 
    [10.000, 12.500) = 145 
    [12.500, 15.000) = 88 
    [15.000, 17.500) = 46 
    [17.500, 20.000) = 3 
    [20.000, 22.500) = 59 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.916 ms/op
     p(50.0000) =      3.330 ms/op
     p(90.0000) =      4.252 ms/op
     p(95.0000) =      4.612 ms/op
     p(99.0000) =      6.078 ms/op
     p(99.9000) =     10.709 ms/op
     p(99.9900) =     21.234 ms/op
     p(99.9990) =     22.185 ms/op
     p(99.9999) =     23.429 ms/op
    p(100.0000) =     23.429 ms/op


# JMH version: 1.21
# VM version: JDK 11.0.19, OpenJDK 64-Bit Server VM, 11.0.19+7
# VM invoker: /usr/lib/jvm/temurin-11-jdk-amd64/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 6.362 ±(99.9%) 0.075 ms/op
# Warmup Iteration   2: 4.736 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.214 ±(99.9%) 0.015 ms/op
Iteration   1: 4.213 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.270 ms/op
                 listUser·p0.50:   3.940 ms/op
                 listUser·p0.90:   5.906 ms/op
                 listUser·p0.95:   6.693 ms/op
                 listUser·p0.99:   8.559 ms/op
                 listUser·p0.999:  14.945 ms/op
                 listUser·p0.9999: 19.177 ms/op
                 listUser·p1.00:   19.923 ms/op

Iteration   2: 4.249 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.094 ms/op
                 listUser·p0.50:   3.990 ms/op
                 listUser·p0.90:   5.759 ms/op
                 listUser·p0.95:   6.619 ms/op
                 listUser·p0.99:   8.503 ms/op
                 listUser·p0.999:  15.659 ms/op
                 listUser·p0.9999: 19.495 ms/op
                 listUser·p1.00:   19.857 ms/op

Iteration   3: 4.213 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.139 ms/op
                 listUser·p0.50:   3.961 ms/op
                 listUser·p0.90:   5.825 ms/op
                 listUser·p0.95:   6.627 ms/op
                 listUser·p0.99:   8.389 ms/op
                 listUser·p0.999:  19.501 ms/op
                 listUser·p0.9999: 21.627 ms/op
                 listUser·p1.00:   22.020 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 227094
  mean =      4.225 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5082 
    [ 2.500,  5.000) = 179981 
    [ 5.000,  7.500) = 36712 
    [ 7.500, 10.000) = 4556 
    [10.000, 12.500) = 363 
    [12.500, 15.000) = 103 
    [15.000, 17.500) = 146 
    [17.500, 20.000) = 97 
    [20.000, 22.500) = 54 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.094 ms/op
     p(50.0000) =      3.961 ms/op
     p(90.0000) =      5.833 ms/op
     p(95.0000) =      6.644 ms/op
     p(99.0000) =      8.487 ms/op
     p(99.9000) =     15.696 ms/op
     p(99.9900) =     21.000 ms/op
     p(99.9990) =     21.946 ms/op
     p(99.9999) =     22.020 ms/op
    p(100.0000) =     22.020 ms/op


# Run complete. Total time: 00:13:14

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   9.376 ± 2.461  ops/ms
ClientGrpc.existUser                       thrpt       3   9.584 ± 1.306  ops/ms
ClientGrpc.getUser                         thrpt       3   9.249 ± 0.529  ops/ms
ClientGrpc.listUser                        thrpt       3   7.553 ± 1.827  ops/ms
ClientGrpc.createUser                       avgt       3   3.399 ± 0.172   ms/op
ClientGrpc.existUser                        avgt       3   3.174 ± 0.858   ms/op
ClientGrpc.getUser                          avgt       3   3.459 ± 0.847   ms/op
ClientGrpc.listUser                         avgt       3   4.224 ± 1.065   ms/op
ClientGrpc.createUser                     sample  284103   3.377 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.617           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.289           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.211           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.563           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.882           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.254           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          22.741           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          23.527           ms/op
ClientGrpc.existUser                      sample  291978   3.286 ± 0.006   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.571           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.211           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.141           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.506           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.128           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          12.091           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          31.884           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          36.438           ms/op
ClientGrpc.getUser                        sample  280350   3.421 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.916           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.330           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.252           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.612           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.078           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          10.709           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          21.234           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          23.429           ms/op
ClientGrpc.listUser                       sample  227094   4.225 ± 0.009   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.094           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.961           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.833           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.644           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.487           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.696           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          21.000           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          22.020           ms/op
