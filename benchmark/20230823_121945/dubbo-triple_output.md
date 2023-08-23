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
# Warmup Iteration   1: 2.095 ops/ms
# Warmup Iteration   2: 5.108 ops/ms
# Warmup Iteration   3: 8.411 ops/ms
Iteration   1: 8.632 ops/ms
Iteration   2: 8.831 ops/ms
Iteration   3: 8.821 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.761 ±(99.9%) 2.047 ops/ms [Average]
  (min, avg, max) = (8.632, 8.761, 8.831), stdev = 0.112
  CI (99.9%): [6.714, 10.809] (assumes normal distribution)


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
# Warmup Iteration   1: 2.755 ops/ms
# Warmup Iteration   2: 7.895 ops/ms
# Warmup Iteration   3: 9.039 ops/ms
Iteration   1: 9.332 ops/ms
Iteration   2: 9.198 ops/ms
Iteration   3: 9.338 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.289 ±(99.9%) 1.444 ops/ms [Average]
  (min, avg, max) = (9.198, 9.289, 9.338), stdev = 0.079
  CI (99.9%): [7.845, 10.733] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:02
# Fork: 1 of 1
# Warmup Iteration   1: 2.947 ops/ms
# Warmup Iteration   2: 7.995 ops/ms
# Warmup Iteration   3: 8.512 ops/ms
Iteration   1: 8.842 ops/ms
Iteration   2: 8.924 ops/ms
Iteration   3: 9.017 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.927 ±(99.9%) 1.597 ops/ms [Average]
  (min, avg, max) = (8.842, 8.927, 9.017), stdev = 0.088
  CI (99.9%): [7.331, 10.524] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 2.507 ops/ms
# Warmup Iteration   2: 6.169 ops/ms
# Warmup Iteration   3: 7.116 ops/ms
Iteration   1: 7.327 ops/ms
Iteration   2: 7.320 ops/ms
Iteration   3: 7.490 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.379 ±(99.9%) 1.753 ops/ms [Average]
  (min, avg, max) = (7.320, 7.379, 7.490), stdev = 0.096
  CI (99.9%): [5.626, 9.132] (assumes normal distribution)


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
# Warmup Iteration   1: 10.969 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 4.175 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.663 ±(99.9%) 0.007 ms/op
Iteration   1: 3.645 ±(99.9%) 0.008 ms/op
Iteration   2: 3.695 ±(99.9%) 0.006 ms/op
Iteration   3: 3.568 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.636 ±(99.9%) 1.168 ms/op [Average]
  (min, avg, max) = (3.568, 3.636, 3.695), stdev = 0.064
  CI (99.9%): [2.468, 4.804] (assumes normal distribution)


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
# Warmup Iteration   1: 8.183 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.826 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.441 ±(99.9%) 0.003 ms/op
Iteration   1: 3.597 ±(99.9%) 0.003 ms/op
Iteration   2: 3.383 ±(99.9%) 0.007 ms/op
Iteration   3: 3.523 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.501 ±(99.9%) 1.978 ms/op [Average]
  (min, avg, max) = (3.383, 3.501, 3.597), stdev = 0.108
  CI (99.9%): [1.523, 5.479] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 10.210 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.879 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.570 ±(99.9%) 0.003 ms/op
Iteration   1: 3.580 ±(99.9%) 0.007 ms/op
Iteration   2: 3.681 ±(99.9%) 0.004 ms/op
Iteration   3: 3.621 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.627 ±(99.9%) 0.919 ms/op [Average]
  (min, avg, max) = (3.580, 3.627, 3.681), stdev = 0.050
  CI (99.9%): [2.708, 4.547] (assumes normal distribution)


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
# Warmup Iteration   1: 11.651 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 5.023 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.417 ±(99.9%) 0.013 ms/op
Iteration   1: 4.352 ±(99.9%) 0.006 ms/op
Iteration   2: 4.114 ±(99.9%) 0.009 ms/op
Iteration   3: 4.220 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.229 ±(99.9%) 2.183 ms/op [Average]
  (min, avg, max) = (4.114, 4.229, 4.352), stdev = 0.120
  CI (99.9%): [2.046, 6.411] (assumes normal distribution)


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
# Warmup Iteration   1: 10.810 ±(99.9%) 0.146 ms/op
# Warmup Iteration   2: 4.107 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 3.977 ±(99.9%) 0.016 ms/op
Iteration   1: 3.802 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.029 ms/op
                 createUser·p0.50:   3.588 ms/op
                 createUser·p0.90:   4.571 ms/op
                 createUser·p0.95:   5.218 ms/op
                 createUser·p0.99:   7.323 ms/op
                 createUser·p0.999:  17.595 ms/op
                 createUser·p0.9999: 27.656 ms/op
                 createUser·p1.00:   28.213 ms/op

Iteration   2: 3.798 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.417 ms/op
                 createUser·p0.50:   3.592 ms/op
                 createUser·p0.90:   4.399 ms/op
                 createUser·p0.95:   5.145 ms/op
                 createUser·p0.99:   7.274 ms/op
                 createUser·p0.999:  28.009 ms/op
                 createUser·p0.9999: 31.757 ms/op
                 createUser·p1.00:   32.211 ms/op

Iteration   3: 3.666 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.043 ms/op
                 createUser·p0.50:   3.469 ms/op
                 createUser·p0.90:   4.186 ms/op
                 createUser·p0.95:   4.588 ms/op
                 createUser·p0.99:   6.775 ms/op
                 createUser·p0.999:  26.935 ms/op
                 createUser·p0.9999: 53.205 ms/op
                 createUser·p1.00:   55.443 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 255429
  mean =      3.755 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 242625 
    [ 5.000, 10.000) = 12000 
    [10.000, 15.000) = 512 
    [15.000, 20.000) = 36 
    [20.000, 25.000) = 1 
    [25.000, 30.000) = 155 
    [30.000, 35.000) = 68 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 0 
    [45.000, 50.000) = 0 
    [50.000, 55.000) = 29 

  Percentiles, ms/op:
      p(0.0000) =      1.029 ms/op
     p(50.0000) =      3.572 ms/op
     p(90.0000) =      4.399 ms/op
     p(95.0000) =      5.005 ms/op
     p(99.0000) =      7.168 ms/op
     p(99.9000) =     24.946 ms/op
     p(99.9900) =     51.112 ms/op
     p(99.9990) =     55.174 ms/op
     p(99.9999) =     55.443 ms/op
    p(100.0000) =     55.443 ms/op


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
# Warmup Iteration   1: 9.595 ±(99.9%) 0.117 ms/op
# Warmup Iteration   2: 3.990 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.516 ±(99.9%) 0.010 ms/op
Iteration   1: 3.429 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.405 ms/op
                 existUser·p0.50:   3.269 ms/op
                 existUser·p0.90:   3.838 ms/op
                 existUser·p0.95:   4.186 ms/op
                 existUser·p0.99:   6.111 ms/op
                 existUser·p0.999:  23.822 ms/op
                 existUser·p0.9999: 27.197 ms/op
                 existUser·p1.00:   27.886 ms/op

Iteration   2: 3.480 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.849 ms/op
                 existUser·p0.50:   3.338 ms/op
                 existUser·p0.90:   3.838 ms/op
                 existUser·p0.95:   4.465 ms/op
                 existUser·p0.99:   7.096 ms/op
                 existUser·p0.999:  15.368 ms/op
                 existUser·p0.9999: 34.223 ms/op
                 existUser·p1.00:   34.603 ms/op

Iteration   3: 3.477 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.225 ms/op
                 existUser·p0.50:   3.310 ms/op
                 existUser·p0.90:   3.834 ms/op
                 existUser·p0.95:   4.383 ms/op
                 existUser·p0.99:   6.480 ms/op
                 existUser·p0.999:  28.705 ms/op
                 existUser·p0.9999: 34.524 ms/op
                 existUser·p1.00:   35.848 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 277180
  mean =      3.462 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6364 
    [ 2.500,  5.000) = 262310 
    [ 5.000,  7.500) = 6781 
    [ 7.500, 10.000) = 1060 
    [10.000, 12.500) = 300 
    [12.500, 15.000) = 71 
    [15.000, 17.500) = 34 
    [17.500, 20.000) = 4 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 96 
    [27.500, 30.000) = 35 
    [30.000, 32.500) = 40 
    [32.500, 35.000) = 69 
    [35.000, 37.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.225 ms/op
     p(50.0000) =      3.314 ms/op
     p(90.0000) =      3.838 ms/op
     p(95.0000) =      4.301 ms/op
     p(99.0000) =      6.676 ms/op
     p(99.9000) =     15.401 ms/op
     p(99.9900) =     34.079 ms/op
     p(99.9990) =     34.976 ms/op
     p(99.9999) =     35.848 ms/op
    p(100.0000) =     35.848 ms/op


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
# Warmup Iteration   1: 9.561 ±(99.9%) 0.147 ms/op
# Warmup Iteration   2: 4.131 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.616 ±(99.9%) 0.012 ms/op
Iteration   1: 3.745 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.048 ms/op
                 getUser·p0.50:   3.502 ms/op
                 getUser·p0.90:   4.194 ms/op
                 getUser·p0.95:   5.571 ms/op
                 getUser·p0.99:   7.799 ms/op
                 getUser·p0.999:  24.871 ms/op
                 getUser·p0.9999: 34.305 ms/op
                 getUser·p1.00:   37.683 ms/op

Iteration   2: 3.611 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.604 ms/op
                 getUser·p0.50:   3.445 ms/op
                 getUser·p0.90:   3.936 ms/op
                 getUser·p0.95:   4.514 ms/op
                 getUser·p0.99:   7.266 ms/op
                 getUser·p0.999:  26.755 ms/op
                 getUser·p0.9999: 29.426 ms/op
                 getUser·p1.00:   29.786 ms/op

Iteration   3: 3.604 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.331 ms/op
                 getUser·p0.50:   3.469 ms/op
                 getUser·p0.90:   3.916 ms/op
                 getUser·p0.95:   4.276 ms/op
                 getUser·p0.99:   6.791 ms/op
                 getUser·p0.999:  24.702 ms/op
                 getUser·p0.9999: 32.944 ms/op
                 getUser·p1.00:   35.324 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 262621
  mean =      3.652 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1473 
    [ 2.500,  5.000) = 248860 
    [ 5.000,  7.500) = 9868 
    [ 7.500, 10.000) = 1468 
    [10.000, 12.500) = 493 
    [12.500, 15.000) = 125 
    [15.000, 17.500) = 42 
    [17.500, 20.000) = 4 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 110 
    [27.500, 30.000) = 85 
    [30.000, 32.500) = 20 
    [32.500, 35.000) = 41 
    [35.000, 37.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      1.048 ms/op
     p(50.0000) =      3.469 ms/op
     p(90.0000) =      4.006 ms/op
     p(95.0000) =      4.792 ms/op
     p(99.0000) =      7.414 ms/op
     p(99.9000) =     24.949 ms/op
     p(99.9900) =     33.882 ms/op
     p(99.9990) =     36.569 ms/op
     p(99.9999) =     37.683 ms/op
    p(100.0000) =     37.683 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 10.648 ±(99.9%) 0.145 ms/op
# Warmup Iteration   2: 4.809 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.458 ±(99.9%) 0.018 ms/op
Iteration   1: 4.366 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.556 ms/op
                 listUser·p0.50:   4.104 ms/op
                 listUser·p0.90:   4.899 ms/op
                 listUser·p0.95:   5.431 ms/op
                 listUser·p0.99:   8.438 ms/op
                 listUser·p0.999:  28.894 ms/op
                 listUser·p0.9999: 34.472 ms/op
                 listUser·p1.00:   35.979 ms/op

Iteration   2: 4.379 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.098 ms/op
                 listUser·p0.50:   4.190 ms/op
                 listUser·p0.90:   4.801 ms/op
                 listUser·p0.95:   5.882 ms/op
                 listUser·p0.99:   8.315 ms/op
                 listUser·p0.999:  18.547 ms/op
                 listUser·p0.9999: 22.086 ms/op
                 listUser·p1.00:   22.905 ms/op

Iteration   3: 4.221 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.433 ms/op
                 listUser·p0.50:   3.981 ms/op
                 listUser·p0.90:   4.653 ms/op
                 listUser·p0.95:   5.014 ms/op
                 listUser·p0.99:   8.471 ms/op
                 listUser·p0.999:  17.400 ms/op
                 listUser·p0.9999: 20.349 ms/op
                 listUser·p1.00:   20.382 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 222143
  mean =      4.321 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 29 
    [ 2.500,  5.000) = 206658 
    [ 5.000,  7.500) = 11961 
    [ 7.500, 10.000) = 2053 
    [10.000, 12.500) = 774 
    [12.500, 15.000) = 189 
    [15.000, 17.500) = 184 
    [17.500, 20.000) = 91 
    [20.000, 22.500) = 75 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 30 
    [27.500, 30.000) = 56 
    [30.000, 32.500) = 10 
    [32.500, 35.000) = 28 
    [35.000, 37.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      1.098 ms/op
     p(50.0000) =      4.092 ms/op
     p(90.0000) =      4.784 ms/op
     p(95.0000) =      5.358 ms/op
     p(99.0000) =      8.421 ms/op
     p(99.9000) =     18.837 ms/op
     p(99.9900) =     33.566 ms/op
     p(99.9990) =     35.754 ms/op
     p(99.9999) =     35.979 ms/op
    p(100.0000) =     35.979 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.761 ± 2.047  ops/ms
ClientPb.existUser                       thrpt       3   9.289 ± 1.444  ops/ms
ClientPb.getUser                         thrpt       3   8.927 ± 1.597  ops/ms
ClientPb.listUser                        thrpt       3   7.379 ± 1.753  ops/ms
ClientPb.createUser                       avgt       3   3.636 ± 1.168   ms/op
ClientPb.existUser                        avgt       3   3.501 ± 1.978   ms/op
ClientPb.getUser                          avgt       3   3.627 ± 0.919   ms/op
ClientPb.listUser                         avgt       3   4.229 ± 2.183   ms/op
ClientPb.createUser                     sample  255429   3.755 ± 0.008   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.029           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.572           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.399           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.005           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.168           ms/op
ClientPb.createUser:createUser·p0.999   sample          24.946           ms/op
ClientPb.createUser:createUser·p0.9999  sample          51.112           ms/op
ClientPb.createUser:createUser·p1.00    sample          55.443           ms/op
ClientPb.existUser                      sample  277180   3.462 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.225           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.314           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.838           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.301           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.676           ms/op
ClientPb.existUser:existUser·p0.999     sample          15.401           ms/op
ClientPb.existUser:existUser·p0.9999    sample          34.079           ms/op
ClientPb.existUser:existUser·p1.00      sample          35.848           ms/op
ClientPb.getUser                        sample  262621   3.652 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.048           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.469           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.006           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.792           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.414           ms/op
ClientPb.getUser:getUser·p0.999         sample          24.949           ms/op
ClientPb.getUser:getUser·p0.9999        sample          33.882           ms/op
ClientPb.getUser:getUser·p1.00          sample          37.683           ms/op
ClientPb.listUser                       sample  222143   4.321 ± 0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.098           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.092           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.784           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.358           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.421           ms/op
ClientPb.listUser:listUser·p0.999       sample          18.837           ms/op
ClientPb.listUser:listUser·p0.9999      sample          33.566           ms/op
ClientPb.listUser:listUser·p1.00        sample          35.979           ms/op
