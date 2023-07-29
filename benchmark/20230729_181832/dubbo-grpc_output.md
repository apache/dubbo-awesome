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
# Warmup Iteration   1: 3.004 ops/ms
# Warmup Iteration   2: 6.985 ops/ms
# Warmup Iteration   3: 8.258 ops/ms
Iteration   1: 8.783 ops/ms
Iteration   2: 8.767 ops/ms
Iteration   3: 8.870 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.807 ±(99.9%) 1.005 ops/ms [Average]
  (min, avg, max) = (8.767, 8.807, 8.870), stdev = 0.055
  CI (99.9%): [7.802, 9.812] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 5.725 ops/ms
# Warmup Iteration   2: 8.811 ops/ms
# Warmup Iteration   3: 9.186 ops/ms
Iteration   1: 9.602 ops/ms
Iteration   2: 9.290 ops/ms
Iteration   3: 9.374 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.422 ±(99.9%) 2.948 ops/ms [Average]
  (min, avg, max) = (9.290, 9.422, 9.602), stdev = 0.162
  CI (99.9%): [6.474, 12.370] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 5.341 ops/ms
# Warmup Iteration   2: 8.334 ops/ms
# Warmup Iteration   3: 8.625 ops/ms
Iteration   1: 8.763 ops/ms
Iteration   2: 8.939 ops/ms
Iteration   3: 8.916 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.873 ±(99.9%) 1.742 ops/ms [Average]
  (min, avg, max) = (8.763, 8.873, 8.939), stdev = 0.095
  CI (99.9%): [7.131, 10.615] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 4.469 ops/ms
# Warmup Iteration   2: 6.225 ops/ms
# Warmup Iteration   3: 6.745 ops/ms
Iteration   1: 6.786 ops/ms
Iteration   2: 6.595 ops/ms
Iteration   3: 6.579 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.653 ±(99.9%) 2.107 ops/ms [Average]
  (min, avg, max) = (6.579, 6.653, 6.786), stdev = 0.116
  CI (99.9%): [4.546, 8.761] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 5.369 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.821 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.789 ±(99.9%) 0.010 ms/op
Iteration   1: 3.596 ±(99.9%) 0.006 ms/op
Iteration   2: 3.655 ±(99.9%) 0.003 ms/op
Iteration   3: 3.618 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.623 ±(99.9%) 0.548 ms/op [Average]
  (min, avg, max) = (3.596, 3.623, 3.655), stdev = 0.030
  CI (99.9%): [3.075, 4.171] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 4.850 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.733 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.489 ±(99.9%) 0.004 ms/op
Iteration   1: 3.417 ±(99.9%) 0.003 ms/op
Iteration   2: 3.396 ±(99.9%) 0.002 ms/op
Iteration   3: 3.545 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.453 ±(99.9%) 1.477 ms/op [Average]
  (min, avg, max) = (3.396, 3.453, 3.545), stdev = 0.081
  CI (99.9%): [1.976, 4.930] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 5.275 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.848 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.752 ±(99.9%) 0.006 ms/op
Iteration   1: 3.614 ±(99.9%) 0.004 ms/op
Iteration   2: 3.641 ±(99.9%) 0.005 ms/op
Iteration   3: 3.594 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.616 ±(99.9%) 0.436 ms/op [Average]
  (min, avg, max) = (3.594, 3.616, 3.641), stdev = 0.024
  CI (99.9%): [3.181, 4.052] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 6.779 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 4.969 ±(99.9%) 0.030 ms/op
# Warmup Iteration   3: 4.845 ±(99.9%) 0.014 ms/op
Iteration   1: 4.771 ±(99.9%) 0.006 ms/op
Iteration   2: 4.757 ±(99.9%) 0.015 ms/op
Iteration   3: 4.725 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.751 ±(99.9%) 0.433 ms/op [Average]
  (min, avg, max) = (4.725, 4.751, 4.771), stdev = 0.024
  CI (99.9%): [4.318, 5.184] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 5.601 ±(99.9%) 0.062 ms/op
# Warmup Iteration   2: 3.926 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.753 ±(99.9%) 0.011 ms/op
Iteration   1: 3.656 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.951 ms/op
                 createUser·p0.50:   3.604 ms/op
                 createUser·p0.90:   4.293 ms/op
                 createUser·p0.95:   4.588 ms/op
                 createUser·p0.99:   5.587 ms/op
                 createUser·p0.999:  10.469 ms/op
                 createUser·p0.9999: 19.152 ms/op
                 createUser·p1.00:   19.562 ms/op

Iteration   2: 3.616 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.785 ms/op
                 createUser·p0.50:   3.596 ms/op
                 createUser·p0.90:   4.202 ms/op
                 createUser·p0.95:   4.456 ms/op
                 createUser·p0.99:   5.434 ms/op
                 createUser·p0.999:  8.454 ms/op
                 createUser·p0.9999: 20.845 ms/op
                 createUser·p1.00:   21.135 ms/op

Iteration   3: 3.604 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.727 ms/op
                 createUser·p0.50:   3.555 ms/op
                 createUser·p0.90:   4.084 ms/op
                 createUser·p0.95:   4.432 ms/op
                 createUser·p0.99:   5.513 ms/op
                 createUser·p0.999:  11.805 ms/op
                 createUser·p0.9999: 25.924 ms/op
                 createUser·p1.00:   26.411 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 264839
  mean =      3.625 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6299 
    [ 2.500,  5.000) = 253462 
    [ 5.000,  7.500) = 4356 
    [ 7.500, 10.000) = 437 
    [10.000, 12.500) = 125 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 44 
    [17.500, 20.000) = 22 
    [20.000, 22.500) = 45 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 18 

  Percentiles, ms/op:
      p(0.0000) =      0.727 ms/op
     p(50.0000) =      3.584 ms/op
     p(90.0000) =      4.202 ms/op
     p(95.0000) =      4.497 ms/op
     p(99.0000) =      5.505 ms/op
     p(99.9000) =     10.177 ms/op
     p(99.9900) =     23.938 ms/op
     p(99.9990) =     26.270 ms/op
     p(99.9999) =     26.411 ms/op
    p(100.0000) =     26.411 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 4.921 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.708 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.539 ±(99.9%) 0.008 ms/op
Iteration   1: 3.507 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.964 ms/op
                 existUser·p0.50:   3.469 ms/op
                 existUser·p0.90:   4.080 ms/op
                 existUser·p0.95:   4.325 ms/op
                 existUser·p0.99:   5.104 ms/op
                 existUser·p0.999:  7.724 ms/op
                 existUser·p0.9999: 17.134 ms/op
                 existUser·p1.00:   17.433 ms/op

Iteration   2: 3.468 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.879 ms/op
                 existUser·p0.50:   3.424 ms/op
                 existUser·p0.90:   4.039 ms/op
                 existUser·p0.95:   4.424 ms/op
                 existUser·p0.99:   5.390 ms/op
                 existUser·p0.999:  8.004 ms/op
                 existUser·p0.9999: 15.086 ms/op
                 existUser·p1.00:   17.170 ms/op

Iteration   3: 3.493 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.993 ms/op
                 existUser·p0.50:   3.453 ms/op
                 existUser·p0.90:   4.039 ms/op
                 existUser·p0.95:   4.309 ms/op
                 existUser·p0.99:   5.439 ms/op
                 existUser·p0.999:  10.805 ms/op
                 existUser·p0.9999: 20.901 ms/op
                 existUser·p1.00:   21.332 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 274922
  mean =      3.489 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7842 
    [ 2.500,  5.000) = 262929 
    [ 5.000,  7.500) = 3625 
    [ 7.500, 10.000) = 273 
    [10.000, 12.500) = 100 
    [12.500, 15.000) = 74 
    [15.000, 17.500) = 47 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.879 ms/op
     p(50.0000) =      3.449 ms/op
     p(90.0000) =      4.055 ms/op
     p(95.0000) =      4.358 ms/op
     p(99.0000) =      5.325 ms/op
     p(99.9000) =      9.522 ms/op
     p(99.9900) =     20.202 ms/op
     p(99.9990) =     21.160 ms/op
     p(99.9999) =     21.332 ms/op
    p(100.0000) =     21.332 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.327 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 3.916 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.715 ±(99.9%) 0.009 ms/op
Iteration   1: 3.682 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.938 ms/op
                 getUser·p0.50:   3.625 ms/op
                 getUser·p0.90:   4.260 ms/op
                 getUser·p0.95:   4.604 ms/op
                 getUser·p0.99:   5.865 ms/op
                 getUser·p0.999:  10.977 ms/op
                 getUser·p0.9999: 22.981 ms/op
                 getUser·p1.00:   23.331 ms/op

Iteration   2: 3.607 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.988 ms/op
                 getUser·p0.50:   3.576 ms/op
                 getUser·p0.90:   4.108 ms/op
                 getUser·p0.95:   4.383 ms/op
                 getUser·p0.99:   5.472 ms/op
                 getUser·p0.999:  8.673 ms/op
                 getUser·p0.9999: 30.717 ms/op
                 getUser·p1.00:   31.130 ms/op

Iteration   3: 3.614 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.033 ms/op
                 getUser·p0.50:   3.572 ms/op
                 getUser·p0.90:   4.182 ms/op
                 getUser·p0.95:   4.465 ms/op
                 getUser·p0.99:   5.603 ms/op
                 getUser·p0.999:  9.990 ms/op
                 getUser·p0.9999: 23.466 ms/op
                 getUser·p1.00:   24.805 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 264111
  mean =      3.634 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5959 
    [ 2.500,  5.000) = 252898 
    [ 5.000,  7.500) = 4618 
    [ 7.500, 10.000) = 371 
    [10.000, 12.500) = 90 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 9 
    [17.500, 20.000) = 40 
    [20.000, 22.500) = 42 
    [22.500, 25.000) = 52 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 13 
    [30.000, 32.500) = 19 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.938 ms/op
     p(50.0000) =      3.588 ms/op
     p(90.0000) =      4.186 ms/op
     p(95.0000) =      4.489 ms/op
     p(99.0000) =      5.669 ms/op
     p(99.9000) =     10.074 ms/op
     p(99.9900) =     28.086 ms/op
     p(99.9990) =     31.010 ms/op
     p(99.9999) =     31.130 ms/op
    p(100.0000) =     31.130 ms/op


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
# Warmup Iteration   1: 7.030 ±(99.9%) 0.075 ms/op
# Warmup Iteration   2: 5.072 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.916 ±(99.9%) 0.014 ms/op
Iteration   1: 4.856 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.978 ms/op
                 listUser·p0.50:   4.686 ms/op
                 listUser·p0.90:   5.816 ms/op
                 listUser·p0.95:   6.726 ms/op
                 listUser·p0.99:   8.651 ms/op
                 listUser·p0.999:  15.816 ms/op
                 listUser·p0.9999: 20.436 ms/op
                 listUser·p1.00:   20.742 ms/op

Iteration   2: 4.810 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.677 ms/op
                 listUser·p0.50:   4.645 ms/op
                 listUser·p0.90:   5.595 ms/op
                 listUser·p0.95:   6.472 ms/op
                 listUser·p0.99:   8.389 ms/op
                 listUser·p0.999:  16.738 ms/op
                 listUser·p0.9999: 28.346 ms/op
                 listUser·p1.00:   28.901 ms/op

Iteration   3: 4.893 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.161 ms/op
                 listUser·p0.50:   4.694 ms/op
                 listUser·p0.90:   5.939 ms/op
                 listUser·p0.95:   6.717 ms/op
                 listUser·p0.99:   8.471 ms/op
                 listUser·p0.999:  24.052 ms/op
                 listUser·p0.9999: 29.375 ms/op
                 listUser·p1.00:   30.278 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 197778
  mean =      4.853 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 97 
    [ 2.500,  5.000) = 144192 
    [ 5.000,  7.500) = 48383 
    [ 7.500, 10.000) = 4462 
    [10.000, 12.500) = 239 
    [12.500, 15.000) = 59 
    [15.000, 17.500) = 141 
    [17.500, 20.000) = 50 
    [20.000, 22.500) = 44 
    [22.500, 25.000) = 33 
    [25.000, 27.500) = 36 
    [27.500, 30.000) = 40 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.161 ms/op
     p(50.0000) =      4.678 ms/op
     p(90.0000) =      5.792 ms/op
     p(95.0000) =      6.644 ms/op
     p(99.0000) =      8.471 ms/op
     p(99.9000) =     17.727 ms/op
     p(99.9900) =     28.661 ms/op
     p(99.9990) =     30.278 ms/op
     p(99.9999) =     30.278 ms/op
    p(100.0000) =     30.278 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.807 ± 1.005  ops/ms
ClientGrpc.existUser                       thrpt       3   9.422 ± 2.948  ops/ms
ClientGrpc.getUser                         thrpt       3   8.873 ± 1.742  ops/ms
ClientGrpc.listUser                        thrpt       3   6.653 ± 2.107  ops/ms
ClientGrpc.createUser                       avgt       3   3.623 ± 0.548   ms/op
ClientGrpc.existUser                        avgt       3   3.453 ± 1.477   ms/op
ClientGrpc.getUser                          avgt       3   3.616 ± 0.436   ms/op
ClientGrpc.listUser                         avgt       3   4.751 ± 0.433   ms/op
ClientGrpc.createUser                     sample  264839   3.625 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.727           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.584           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.202           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.497           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.505           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.177           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          23.938           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          26.411           ms/op
ClientGrpc.existUser                      sample  274922   3.489 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.879           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.449           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.055           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.358           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.325           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           9.522           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          20.202           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          21.332           ms/op
ClientGrpc.getUser                        sample  264111   3.634 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.938           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.588           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.186           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.489           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.669           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          10.074           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          28.086           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          31.130           ms/op
ClientGrpc.listUser                       sample  197778   4.853 ± 0.008   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.161           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.678           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.792           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.644           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.471           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.727           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          28.661           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          30.278           ms/op
