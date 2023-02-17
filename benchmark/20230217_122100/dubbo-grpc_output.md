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
# Warmup Iteration   1: 3.329 ops/ms
# Warmup Iteration   2: 7.106 ops/ms
# Warmup Iteration   3: 8.097 ops/ms
Iteration   1: 8.322 ops/ms
Iteration   2: 8.223 ops/ms
Iteration   3: 8.257 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.267 ±(99.9%) 0.916 ops/ms [Average]
  (min, avg, max) = (8.223, 8.267, 8.322), stdev = 0.050
  CI (99.9%): [7.351, 9.183] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:03
# Fork: 1 of 1
# Warmup Iteration   1: 5.897 ops/ms
# Warmup Iteration   2: 8.321 ops/ms
# Warmup Iteration   3: 8.538 ops/ms
Iteration   1: 8.608 ops/ms
Iteration   2: 8.781 ops/ms
Iteration   3: 8.549 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.646 ±(99.9%) 2.202 ops/ms [Average]
  (min, avg, max) = (8.549, 8.646, 8.781), stdev = 0.121
  CI (99.9%): [6.444, 10.848] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 5.423 ops/ms
# Warmup Iteration   2: 7.819 ops/ms
# Warmup Iteration   3: 8.093 ops/ms
Iteration   1: 8.080 ops/ms
Iteration   2: 8.289 ops/ms
Iteration   3: 7.980 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.116 ±(99.9%) 2.878 ops/ms [Average]
  (min, avg, max) = (7.980, 8.116, 8.289), stdev = 0.158
  CI (99.9%): [5.238, 10.995] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 4.219 ops/ms
# Warmup Iteration   2: 6.067 ops/ms
# Warmup Iteration   3: 6.311 ops/ms
Iteration   1: 6.677 ops/ms
Iteration   2: 6.529 ops/ms
Iteration   3: 6.515 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.574 ±(99.9%) 1.635 ops/ms [Average]
  (min, avg, max) = (6.515, 6.574, 6.677), stdev = 0.090
  CI (99.9%): [4.939, 8.209] (assumes normal distribution)


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
# Warmup Iteration   1: 5.638 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 4.006 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 4.017 ±(99.9%) 0.005 ms/op
Iteration   1: 4.071 ±(99.9%) 0.004 ms/op
Iteration   2: 4.011 ±(99.9%) 0.002 ms/op
Iteration   3: 4.039 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.040 ±(99.9%) 0.550 ms/op [Average]
  (min, avg, max) = (4.011, 4.040, 4.071), stdev = 0.030
  CI (99.9%): [3.490, 4.590] (assumes normal distribution)


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
# Warmup Iteration   1: 4.745 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.868 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.717 ±(99.9%) 0.005 ms/op
Iteration   1: 3.556 ±(99.9%) 0.004 ms/op
Iteration   2: 3.753 ±(99.9%) 0.004 ms/op
Iteration   3: 3.674 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.661 ±(99.9%) 1.810 ms/op [Average]
  (min, avg, max) = (3.556, 3.661, 3.753), stdev = 0.099
  CI (99.9%): [1.851, 5.471] (assumes normal distribution)


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
# Warmup Iteration   1: 4.969 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 4.041 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.858 ±(99.9%) 0.006 ms/op
Iteration   1: 3.869 ±(99.9%) 0.004 ms/op
Iteration   2: 3.769 ±(99.9%) 0.004 ms/op
Iteration   3: 3.816 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.818 ±(99.9%) 0.916 ms/op [Average]
  (min, avg, max) = (3.769, 3.818, 3.869), stdev = 0.050
  CI (99.9%): [2.902, 4.734] (assumes normal distribution)


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
# Warmup Iteration   1: 6.753 ±(99.9%) 0.062 ms/op
# Warmup Iteration   2: 5.205 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 5.208 ±(99.9%) 0.030 ms/op
Iteration   1: 5.049 ±(99.9%) 0.023 ms/op
Iteration   2: 5.331 ±(99.9%) 0.022 ms/op
Iteration   3: 5.091 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.157 ±(99.9%) 2.773 ms/op [Average]
  (min, avg, max) = (5.049, 5.157, 5.331), stdev = 0.152
  CI (99.9%): [2.384, 7.930] (assumes normal distribution)


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
# Warmup Iteration   1: 5.372 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 4.006 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.791 ±(99.9%) 0.009 ms/op
Iteration   1: 3.911 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.032 ms/op
                 createUser·p0.50:   3.834 ms/op
                 createUser·p0.90:   4.751 ms/op
                 createUser·p0.95:   5.120 ms/op
                 createUser·p0.99:   6.627 ms/op
                 createUser·p0.999:  11.144 ms/op
                 createUser·p0.9999: 21.347 ms/op
                 createUser·p1.00:   21.791 ms/op

Iteration   2: 3.944 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.998 ms/op
                 createUser·p0.50:   3.879 ms/op
                 createUser·p0.90:   4.891 ms/op
                 createUser·p0.95:   5.218 ms/op
                 createUser·p0.99:   6.480 ms/op
                 createUser·p0.999:  11.420 ms/op
                 createUser·p0.9999: 15.496 ms/op
                 createUser·p1.00:   19.661 ms/op

Iteration   3: 3.842 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.829 ms/op
                 createUser·p0.50:   3.789 ms/op
                 createUser·p0.90:   4.628 ms/op
                 createUser·p0.95:   4.956 ms/op
                 createUser·p0.99:   6.447 ms/op
                 createUser·p0.999:  14.214 ms/op
                 createUser·p0.9999: 19.726 ms/op
                 createUser·p1.00:   21.266 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 246069
  mean =      3.898 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7587 
    [ 2.500,  5.000) = 223214 
    [ 5.000,  7.500) = 13983 
    [ 7.500, 10.000) = 901 
    [10.000, 12.500) = 183 
    [12.500, 15.000) = 65 
    [15.000, 17.500) = 68 
    [17.500, 20.000) = 33 
    [20.000, 22.500) = 35 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.829 ms/op
     p(50.0000) =      3.834 ms/op
     p(90.0000) =      4.760 ms/op
     p(95.0000) =      5.112 ms/op
     p(99.0000) =      6.504 ms/op
     p(99.9000) =     11.287 ms/op
     p(99.9900) =     20.689 ms/op
     p(99.9990) =     21.662 ms/op
     p(99.9999) =     21.791 ms/op
    p(100.0000) =     21.791 ms/op


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
# Warmup Iteration   1: 4.971 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.975 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.889 ±(99.9%) 0.012 ms/op
Iteration   1: 3.726 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.966 ms/op
                 existUser·p0.50:   3.682 ms/op
                 existUser·p0.90:   4.563 ms/op
                 existUser·p0.95:   4.866 ms/op
                 existUser·p0.99:   6.169 ms/op
                 existUser·p0.999:  11.603 ms/op
                 existUser·p0.9999: 14.415 ms/op
                 existUser·p1.00:   14.598 ms/op

Iteration   2: 3.784 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.623 ms/op
                 existUser·p0.50:   3.731 ms/op
                 existUser·p0.90:   4.604 ms/op
                 existUser·p0.95:   4.833 ms/op
                 existUser·p0.99:   6.078 ms/op
                 existUser·p0.999:  10.737 ms/op
                 existUser·p0.9999: 21.302 ms/op
                 existUser·p1.00:   21.692 ms/op

Iteration   3: 3.710 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.829 ms/op
                 existUser·p0.50:   3.654 ms/op
                 existUser·p0.90:   4.424 ms/op
                 existUser·p0.95:   4.702 ms/op
                 existUser·p0.99:   5.980 ms/op
                 existUser·p0.999:  11.229 ms/op
                 existUser·p0.9999: 19.096 ms/op
                 existUser·p1.00:   21.103 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 256565
  mean =      3.740 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8465 
    [ 2.500,  5.000) = 239818 
    [ 5.000,  7.500) = 7183 
    [ 7.500, 10.000) = 772 
    [10.000, 12.500) = 137 
    [12.500, 15.000) = 119 
    [15.000, 17.500) = 7 
    [17.500, 20.000) = 37 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.623 ms/op
     p(50.0000) =      3.686 ms/op
     p(90.0000) =      4.538 ms/op
     p(95.0000) =      4.801 ms/op
     p(99.0000) =      6.078 ms/op
     p(99.9000) =     11.247 ms/op
     p(99.9900) =     20.548 ms/op
     p(99.9990) =     21.590 ms/op
     p(99.9999) =     21.692 ms/op
    p(100.0000) =     21.692 ms/op


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
# Warmup Iteration   1: 5.282 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 4.016 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.986 ±(99.9%) 0.010 ms/op
Iteration   1: 3.930 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.075 ms/op
                 getUser·p0.50:   3.830 ms/op
                 getUser·p0.90:   4.751 ms/op
                 getUser·p0.95:   5.145 ms/op
                 getUser·p0.99:   6.939 ms/op
                 getUser·p0.999:  11.033 ms/op
                 getUser·p0.9999: 18.018 ms/op
                 getUser·p1.00:   19.202 ms/op

Iteration   2: 4.013 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.002 ms/op
                 getUser·p0.50:   3.957 ms/op
                 getUser·p0.90:   5.054 ms/op
                 getUser·p0.95:   5.382 ms/op
                 getUser·p0.99:   6.889 ms/op
                 getUser·p0.999:  9.542 ms/op
                 getUser·p0.9999: 18.089 ms/op
                 getUser·p1.00:   18.481 ms/op

Iteration   3: 4.028 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.515 ms/op
                 getUser·p0.50:   3.969 ms/op
                 getUser·p0.90:   4.989 ms/op
                 getUser·p0.95:   5.308 ms/op
                 getUser·p0.99:   6.857 ms/op
                 getUser·p0.999:  12.075 ms/op
                 getUser·p0.9999: 19.476 ms/op
                 getUser·p1.00:   20.120 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 240415
  mean =      3.990 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7917 
    [ 2.500,  5.000) = 210669 
    [ 5.000,  7.500) = 20187 
    [ 7.500, 10.000) = 1302 
    [10.000, 12.500) = 183 
    [12.500, 15.000) = 50 
    [15.000, 17.500) = 69 
    [17.500, 20.000) = 35 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.515 ms/op
     p(50.0000) =      3.912 ms/op
     p(90.0000) =      4.956 ms/op
     p(95.0000) =      5.292 ms/op
     p(99.0000) =      6.889 ms/op
     p(99.9000) =     10.633 ms/op
     p(99.9900) =     18.119 ms/op
     p(99.9990) =     20.041 ms/op
     p(99.9999) =     20.120 ms/op
    p(100.0000) =     20.120 ms/op


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
# Warmup Iteration   1: 6.877 ±(99.9%) 0.069 ms/op
# Warmup Iteration   2: 5.159 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.905 ±(99.9%) 0.016 ms/op
Iteration   1: 4.825 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.029 ms/op
                 listUser·p0.50:   4.669 ms/op
                 listUser·p0.90:   5.833 ms/op
                 listUser·p0.95:   6.636 ms/op
                 listUser·p0.99:   8.733 ms/op
                 listUser·p0.999:  14.975 ms/op
                 listUser·p0.9999: 22.741 ms/op
                 listUser·p1.00:   23.003 ms/op

Iteration   2: 4.799 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.329 ms/op
                 listUser·p0.50:   4.637 ms/op
                 listUser·p0.90:   5.816 ms/op
                 listUser·p0.95:   6.758 ms/op
                 listUser·p0.99:   8.569 ms/op
                 listUser·p0.999:  16.570 ms/op
                 listUser·p0.9999: 19.791 ms/op
                 listUser·p1.00:   21.234 ms/op

Iteration   3: 4.940 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   0.413 ms/op
                 listUser·p0.50:   4.710 ms/op
                 listUser·p0.90:   6.390 ms/op
                 listUser·p0.95:   7.029 ms/op
                 listUser·p0.99:   8.634 ms/op
                 listUser·p0.999:  20.362 ms/op
                 listUser·p0.9999: 27.361 ms/op
                 listUser·p1.00:   29.393 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 197875
  mean =      4.854 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 434 
    [ 2.500,  5.000) = 139174 
    [ 5.000,  7.500) = 52752 
    [ 7.500, 10.000) = 4706 
    [10.000, 12.500) = 423 
    [12.500, 15.000) = 127 
    [15.000, 17.500) = 80 
    [17.500, 20.000) = 66 
    [20.000, 22.500) = 64 
    [22.500, 25.000) = 17 
    [25.000, 27.500) = 29 

  Percentiles, ms/op:
      p(0.0000) =      0.413 ms/op
     p(50.0000) =      4.669 ms/op
     p(90.0000) =      6.070 ms/op
     p(95.0000) =      6.840 ms/op
     p(99.0000) =      8.618 ms/op
     p(99.9000) =     16.728 ms/op
     p(99.9900) =     26.909 ms/op
     p(99.9990) =     28.848 ms/op
     p(99.9999) =     29.393 ms/op
    p(100.0000) =     29.393 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.267 ± 0.916  ops/ms
ClientGrpc.existUser                       thrpt       3   8.646 ± 2.202  ops/ms
ClientGrpc.getUser                         thrpt       3   8.116 ± 2.878  ops/ms
ClientGrpc.listUser                        thrpt       3   6.574 ± 1.635  ops/ms
ClientGrpc.createUser                       avgt       3   4.040 ± 0.550   ms/op
ClientGrpc.existUser                        avgt       3   3.661 ± 1.810   ms/op
ClientGrpc.getUser                          avgt       3   3.818 ± 0.916   ms/op
ClientGrpc.listUser                         avgt       3   5.157 ± 2.773   ms/op
ClientGrpc.createUser                     sample  246069   3.898 ± 0.006   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.829           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.834           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.760           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.112           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.504           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.287           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          20.689           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          21.791           ms/op
ClientGrpc.existUser                      sample  256565   3.740 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.623           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.686           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.538           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.801           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.078           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          11.247           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          20.548           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          21.692           ms/op
ClientGrpc.getUser                        sample  240415   3.990 ± 0.006   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.515           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.912           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.956           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.292           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.889           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          10.633           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.119           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.120           ms/op
ClientGrpc.listUser                       sample  197875   4.854 ± 0.009   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.413           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.669           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.070           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.840           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.618           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.728           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          26.909           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          29.393           ms/op
