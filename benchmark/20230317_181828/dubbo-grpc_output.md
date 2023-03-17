# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.128 ops/ms
# Warmup Iteration   2: 7.315 ops/ms
# Warmup Iteration   3: 8.641 ops/ms
Iteration   1: 8.866 ops/ms
Iteration   2: 9.073 ops/ms
Iteration   3: 9.129 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  9.023 ±(99.9%) 2.528 ops/ms [Average]
  (min, avg, max) = (8.866, 9.023, 9.129), stdev = 0.139
  CI (99.9%): [6.495, 11.550] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:12:01
# Fork: 1 of 1
# Warmup Iteration   1: 6.280 ops/ms
# Warmup Iteration   2: 8.689 ops/ms
# Warmup Iteration   3: 9.330 ops/ms
Iteration   1: 9.613 ops/ms
Iteration   2: 9.341 ops/ms
Iteration   3: 9.542 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.499 ±(99.9%) 2.574 ops/ms [Average]
  (min, avg, max) = (9.341, 9.499, 9.613), stdev = 0.141
  CI (99.9%): [6.925, 12.073] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:54
# Fork: 1 of 1
# Warmup Iteration   1: 5.889 ops/ms
# Warmup Iteration   2: 8.705 ops/ms
# Warmup Iteration   3: 8.817 ops/ms
Iteration   1: 9.040 ops/ms
Iteration   2: 8.901 ops/ms
Iteration   3: 9.194 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  9.045 ±(99.9%) 2.673 ops/ms [Average]
  (min, avg, max) = (8.901, 9.045, 9.194), stdev = 0.147
  CI (99.9%): [6.372, 11.718] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 4.872 ops/ms
# Warmup Iteration   2: 6.213 ops/ms
# Warmup Iteration   3: 6.825 ops/ms
Iteration   1: 6.869 ops/ms
Iteration   2: 6.877 ops/ms
Iteration   3: 6.782 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.842 ±(99.9%) 0.965 ops/ms [Average]
  (min, avg, max) = (6.782, 6.842, 6.877), stdev = 0.053
  CI (99.9%): [5.877, 7.808] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 4.927 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.756 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 3.554 ±(99.9%) 0.003 ms/op
Iteration   1: 3.538 ±(99.9%) 0.003 ms/op
Iteration   2: 3.500 ±(99.9%) 0.003 ms/op
Iteration   3: 3.552 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.530 ±(99.9%) 0.489 ms/op [Average]
  (min, avg, max) = (3.500, 3.530, 3.552), stdev = 0.027
  CI (99.9%): [3.041, 4.019] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 4.717 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.517 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.428 ±(99.9%) 0.003 ms/op
Iteration   1: 3.367 ±(99.9%) 0.003 ms/op
Iteration   2: 3.383 ±(99.9%) 0.002 ms/op
Iteration   3: 3.410 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.386 ±(99.9%) 0.397 ms/op [Average]
  (min, avg, max) = (3.367, 3.386, 3.410), stdev = 0.022
  CI (99.9%): [2.989, 3.784] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 5.074 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.784 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.607 ±(99.9%) 0.005 ms/op
Iteration   1: 3.491 ±(99.9%) 0.005 ms/op
Iteration   2: 3.521 ±(99.9%) 0.006 ms/op
Iteration   3: 3.529 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.514 ±(99.9%) 0.365 ms/op [Average]
  (min, avg, max) = (3.491, 3.514, 3.529), stdev = 0.020
  CI (99.9%): [3.148, 3.879] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 6.829 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 4.790 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.745 ±(99.9%) 0.016 ms/op
Iteration   1: 4.702 ±(99.9%) 0.013 ms/op
Iteration   2: 4.754 ±(99.9%) 0.020 ms/op
Iteration   3: 4.614 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.690 ±(99.9%) 1.292 ms/op [Average]
  (min, avg, max) = (4.614, 4.690, 4.754), stdev = 0.071
  CI (99.9%): [3.398, 5.982] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 5.395 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 3.900 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.683 ±(99.9%) 0.008 ms/op
Iteration   1: 3.598 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.863 ms/op
                 createUser·p0.50:   3.523 ms/op
                 createUser·p0.90:   4.227 ms/op
                 createUser·p0.95:   4.571 ms/op
                 createUser·p0.99:   5.759 ms/op
                 createUser·p0.999:  13.044 ms/op
                 createUser·p0.9999: 16.340 ms/op
                 createUser·p1.00:   16.663 ms/op

Iteration   2: 3.516 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.106 ms/op
                 createUser·p0.50:   3.478 ms/op
                 createUser·p0.90:   3.916 ms/op
                 createUser·p0.95:   4.125 ms/op
                 createUser·p0.99:   4.932 ms/op
                 createUser·p0.999:  9.257 ms/op
                 createUser·p0.9999: 16.546 ms/op
                 createUser·p1.00:   17.007 ms/op

Iteration   3: 3.553 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.899 ms/op
                 createUser·p0.50:   3.494 ms/op
                 createUser·p0.90:   4.166 ms/op
                 createUser·p0.95:   4.473 ms/op
                 createUser·p0.99:   5.325 ms/op
                 createUser·p0.999:  13.617 ms/op
                 createUser·p0.9999: 26.772 ms/op
                 createUser·p1.00:   27.132 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 269865
  mean =      3.555 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3983 
    [ 2.500,  5.000) = 261421 
    [ 5.000,  7.500) = 3731 
    [ 7.500, 10.000) = 419 
    [10.000, 12.500) = 40 
    [12.500, 15.000) = 128 
    [15.000, 17.500) = 103 
    [17.500, 20.000) = 8 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 31 

  Percentiles, ms/op:
      p(0.0000) =      0.863 ms/op
     p(50.0000) =      3.494 ms/op
     p(90.0000) =      4.100 ms/op
     p(95.0000) =      4.407 ms/op
     p(99.0000) =      5.407 ms/op
     p(99.9000) =     12.774 ms/op
     p(99.9900) =     25.726 ms/op
     p(99.9990) =     27.076 ms/op
     p(99.9999) =     27.132 ms/op
    p(100.0000) =     27.132 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 4.930 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 3.679 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.399 ±(99.9%) 0.008 ms/op
Iteration   1: 3.432 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   1.006 ms/op
                 existUser·p0.50:   3.387 ms/op
                 existUser·p0.90:   3.957 ms/op
                 existUser·p0.95:   4.194 ms/op
                 existUser·p0.99:   5.226 ms/op
                 existUser·p0.999:  8.115 ms/op
                 existUser·p0.9999: 15.969 ms/op
                 existUser·p1.00:   16.351 ms/op

Iteration   2: 3.377 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.600 ms/op
                 existUser·p0.50:   3.367 ms/op
                 existUser·p0.90:   3.998 ms/op
                 existUser·p0.95:   4.243 ms/op
                 existUser·p0.99:   5.480 ms/op
                 existUser·p0.999:  8.503 ms/op
                 existUser·p0.9999: 24.036 ms/op
                 existUser·p1.00:   24.478 ms/op

Iteration   3: 3.399 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.984 ms/op
                 existUser·p0.50:   3.371 ms/op
                 existUser·p0.90:   3.838 ms/op
                 existUser·p0.95:   4.145 ms/op
                 existUser·p0.99:   5.439 ms/op
                 existUser·p0.999:  7.991 ms/op
                 existUser·p0.9999: 18.173 ms/op
                 existUser·p1.00:   19.497 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 282027
  mean =      3.402 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10023 
    [ 2.500,  5.000) = 267998 
    [ 5.000,  7.500) = 3599 
    [ 7.500, 10.000) = 247 
    [10.000, 12.500) = 16 
    [12.500, 15.000) = 16 
    [15.000, 17.500) = 70 
    [17.500, 20.000) = 26 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.600 ms/op
     p(50.0000) =      3.375 ms/op
     p(90.0000) =      3.936 ms/op
     p(95.0000) =      4.202 ms/op
     p(99.0000) =      5.366 ms/op
     p(99.9000) =      8.175 ms/op
     p(99.9900) =     23.422 ms/op
     p(99.9990) =     24.332 ms/op
     p(99.9999) =     24.478 ms/op
    p(100.0000) =     24.478 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 4.888 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.795 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.649 ±(99.9%) 0.009 ms/op
Iteration   1: 3.653 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.048 ms/op
                 getUser·p0.50:   3.584 ms/op
                 getUser·p0.90:   4.375 ms/op
                 getUser·p0.95:   4.686 ms/op
                 getUser·p0.99:   5.915 ms/op
                 getUser·p0.999:  8.831 ms/op
                 getUser·p0.9999: 23.215 ms/op
                 getUser·p1.00:   24.609 ms/op

Iteration   2: 3.612 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.710 ms/op
                 getUser·p0.50:   3.547 ms/op
                 getUser·p0.90:   4.276 ms/op
                 getUser·p0.95:   4.588 ms/op
                 getUser·p0.99:   5.554 ms/op
                 getUser·p0.999:  8.182 ms/op
                 getUser·p0.9999: 18.752 ms/op
                 getUser·p1.00:   19.268 ms/op

Iteration   3: 3.606 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.528 ms/op
                 getUser·p0.50:   3.543 ms/op
                 getUser·p0.90:   4.219 ms/op
                 getUser·p0.95:   4.489 ms/op
                 getUser·p0.99:   5.300 ms/op
                 getUser·p0.999:  8.481 ms/op
                 getUser·p0.9999: 22.290 ms/op
                 getUser·p1.00:   24.019 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 265054
  mean =      3.623 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5025 
    [ 2.500,  5.000) = 254336 
    [ 5.000,  7.500) = 5265 
    [ 7.500, 10.000) = 263 
    [10.000, 12.500) = 5 
    [12.500, 15.000) = 31 
    [15.000, 17.500) = 9 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 67 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.528 ms/op
     p(50.0000) =      3.555 ms/op
     p(90.0000) =      4.284 ms/op
     p(95.0000) =      4.596 ms/op
     p(99.0000) =      5.612 ms/op
     p(99.9000) =      8.552 ms/op
     p(99.9900) =     22.561 ms/op
     p(99.9990) =     24.512 ms/op
     p(99.9999) =     24.609 ms/op
    p(100.0000) =     24.609 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 6.407 ±(99.9%) 0.068 ms/op
# Warmup Iteration   2: 4.896 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.683 ±(99.9%) 0.013 ms/op
Iteration   1: 4.655 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.540 ms/op
                 listUser·p0.50:   4.473 ms/op
                 listUser·p0.90:   5.890 ms/op
                 listUser·p0.95:   6.791 ms/op
                 listUser·p0.99:   8.349 ms/op
                 listUser·p0.999:  14.942 ms/op
                 listUser·p0.9999: 16.599 ms/op
                 listUser·p1.00:   17.072 ms/op

Iteration   2: 4.734 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.239 ms/op
                 listUser·p0.50:   4.522 ms/op
                 listUser·p0.90:   5.898 ms/op
                 listUser·p0.95:   6.676 ms/op
                 listUser·p0.99:   8.471 ms/op
                 listUser·p0.999:  17.968 ms/op
                 listUser·p0.9999: 19.971 ms/op
                 listUser·p1.00:   21.168 ms/op

Iteration   3: 4.664 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.303 ms/op
                 listUser·p0.50:   4.432 ms/op
                 listUser·p0.90:   5.906 ms/op
                 listUser·p0.95:   6.701 ms/op
                 listUser·p0.99:   8.585 ms/op
                 listUser·p0.999:  18.393 ms/op
                 listUser·p0.9999: 21.795 ms/op
                 listUser·p1.00:   22.708 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 204890
  mean =      4.684 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 542 
    [ 2.500,  5.000) = 160311 
    [ 5.000,  7.500) = 39159 
    [ 7.500, 10.000) = 3928 
    [10.000, 12.500) = 491 
    [12.500, 15.000) = 135 
    [15.000, 17.500) = 143 
    [17.500, 20.000) = 152 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.239 ms/op
     p(50.0000) =      4.481 ms/op
     p(90.0000) =      5.898 ms/op
     p(95.0000) =      6.726 ms/op
     p(99.0000) =      8.454 ms/op
     p(99.9000) =     17.105 ms/op
     p(99.9900) =     21.119 ms/op
     p(99.9990) =     22.653 ms/op
     p(99.9999) =     22.708 ms/op
    p(100.0000) =     22.708 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   9.023 ± 2.528  ops/ms
ClientGrpc.existUser                       thrpt       3   9.499 ± 2.574  ops/ms
ClientGrpc.getUser                         thrpt       3   9.045 ± 2.673  ops/ms
ClientGrpc.listUser                        thrpt       3   6.842 ± 0.965  ops/ms
ClientGrpc.createUser                       avgt       3   3.530 ± 0.489   ms/op
ClientGrpc.existUser                        avgt       3   3.386 ± 0.397   ms/op
ClientGrpc.getUser                          avgt       3   3.514 ± 0.365   ms/op
ClientGrpc.listUser                         avgt       3   4.690 ± 1.292   ms/op
ClientGrpc.createUser                     sample  269865   3.555 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.863           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.494           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.100           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.407           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.407           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.774           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          25.726           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          27.132           ms/op
ClientGrpc.existUser                      sample  282027   3.402 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.600           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.375           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.936           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.202           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.366           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.175           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          23.422           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          24.478           ms/op
ClientGrpc.getUser                        sample  265054   3.623 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.528           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.555           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.284           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.596           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.612           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.552           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          22.561           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          24.609           ms/op
ClientGrpc.listUser                       sample  204890   4.684 ± 0.008   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.239           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.481           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.898           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.726           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.454           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.105           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          21.119           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          22.708           ms/op
