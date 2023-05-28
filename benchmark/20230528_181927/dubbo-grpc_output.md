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
# Warmup Iteration   1: 4.344 ops/ms
# Warmup Iteration   2: 9.484 ops/ms
# Warmup Iteration   3: 10.099 ops/ms
Iteration   1: 10.435 ops/ms
Iteration   2: 10.819 ops/ms
Iteration   3: 10.653 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.636 ±(99.9%) 3.517 ops/ms [Average]
  (min, avg, max) = (10.435, 10.636, 10.819), stdev = 0.193
  CI (99.9%): [7.119, 14.153] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 8.037 ops/ms
# Warmup Iteration   2: 10.921 ops/ms
# Warmup Iteration   3: 11.765 ops/ms
Iteration   1: 11.017 ops/ms
Iteration   2: 11.251 ops/ms
Iteration   3: 11.358 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.208 ±(99.9%) 3.181 ops/ms [Average]
  (min, avg, max) = (11.017, 11.208, 11.358), stdev = 0.174
  CI (99.9%): [8.027, 14.390] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.225 ops/ms
# Warmup Iteration   2: 10.408 ops/ms
# Warmup Iteration   3: 10.689 ops/ms
Iteration   1: 10.618 ops/ms
Iteration   2: 10.640 ops/ms
Iteration   3: 10.755 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.671 ±(99.9%) 1.340 ops/ms [Average]
  (min, avg, max) = (10.618, 10.671, 10.755), stdev = 0.073
  CI (99.9%): [9.331, 12.010] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:45
# Fork: 1 of 1
# Warmup Iteration   1: 5.696 ops/ms
# Warmup Iteration   2: 7.907 ops/ms
# Warmup Iteration   3: 8.146 ops/ms
Iteration   1: 8.156 ops/ms
Iteration   2: 8.208 ops/ms
Iteration   3: 8.168 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.177 ±(99.9%) 0.502 ops/ms [Average]
  (min, avg, max) = (8.156, 8.177, 8.208), stdev = 0.028
  CI (99.9%): [7.675, 8.679] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:40
# Fork: 1 of 1
# Warmup Iteration   1: 4.107 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.105 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.025 ±(99.9%) 0.004 ms/op
Iteration   1: 2.997 ±(99.9%) 0.009 ms/op
Iteration   2: 2.980 ±(99.9%) 0.003 ms/op
Iteration   3: 2.983 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.986 ±(99.9%) 0.164 ms/op [Average]
  (min, avg, max) = (2.980, 2.986, 2.997), stdev = 0.009
  CI (99.9%): [2.823, 3.150] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.993 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.949 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.892 ±(99.9%) 0.001 ms/op
Iteration   1: 2.860 ±(99.9%) 0.003 ms/op
Iteration   2: 2.916 ±(99.9%) 0.001 ms/op
Iteration   3: 2.822 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.866 ±(99.9%) 0.863 ms/op [Average]
  (min, avg, max) = (2.822, 2.866, 2.916), stdev = 0.047
  CI (99.9%): [2.003, 3.730] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 3.970 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.140 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.061 ±(99.9%) 0.002 ms/op
Iteration   1: 2.993 ±(99.9%) 0.003 ms/op
Iteration   2: 2.971 ±(99.9%) 0.004 ms/op
Iteration   3: 2.978 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.981 ±(99.9%) 0.206 ms/op [Average]
  (min, avg, max) = (2.971, 2.981, 2.993), stdev = 0.011
  CI (99.9%): [2.774, 3.187] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 4.715 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 4.094 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.891 ±(99.9%) 0.013 ms/op
Iteration   1: 3.882 ±(99.9%) 0.013 ms/op
Iteration   2: 3.826 ±(99.9%) 0.025 ms/op
Iteration   3: 3.937 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.882 ±(99.9%) 1.014 ms/op [Average]
  (min, avg, max) = (3.826, 3.882, 3.937), stdev = 0.056
  CI (99.9%): [2.868, 4.896] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.123 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.041 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.027 ±(99.9%) 0.007 ms/op
Iteration   1: 3.019 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.722 ms/op
                 createUser·p0.50:   2.970 ms/op
                 createUser·p0.90:   3.596 ms/op
                 createUser·p0.95:   3.805 ms/op
                 createUser·p0.99:   4.719 ms/op
                 createUser·p0.999:  8.436 ms/op
                 createUser·p0.9999: 18.887 ms/op
                 createUser·p1.00:   20.382 ms/op

Iteration   2: 3.067 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.729 ms/op
                 createUser·p0.50:   3.002 ms/op
                 createUser·p0.90:   3.748 ms/op
                 createUser·p0.95:   3.891 ms/op
                 createUser·p0.99:   4.588 ms/op
                 createUser·p0.999:  6.699 ms/op
                 createUser·p0.9999: 23.331 ms/op
                 createUser·p1.00:   23.888 ms/op

Iteration   3: 2.933 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.700 ms/op
                 createUser·p0.50:   2.912 ms/op
                 createUser·p0.90:   3.412 ms/op
                 createUser·p0.95:   3.690 ms/op
                 createUser·p0.99:   4.604 ms/op
                 createUser·p0.999:  7.950 ms/op
                 createUser·p0.9999: 20.322 ms/op
                 createUser·p1.00:   20.840 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 319540
  mean =      3.005 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 33771 
    [ 2.500,  5.000) = 284126 
    [ 5.000,  7.500) = 1236 
    [ 7.500, 10.000) = 169 
    [10.000, 12.500) = 44 
    [12.500, 15.000) = 2 
    [15.000, 17.500) = 57 
    [17.500, 20.000) = 85 
    [20.000, 22.500) = 37 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.700 ms/op
     p(50.0000) =      2.957 ms/op
     p(90.0000) =      3.617 ms/op
     p(95.0000) =      3.834 ms/op
     p(99.0000) =      4.637 ms/op
     p(99.9000) =      7.922 ms/op
     p(99.9900) =     21.407 ms/op
     p(99.9990) =     23.462 ms/op
     p(99.9999) =     23.888 ms/op
    p(100.0000) =     23.888 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.865 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 2.966 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.889 ±(99.9%) 0.005 ms/op
Iteration   1: 2.854 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.304 ms/op
                 existUser·p0.50:   2.834 ms/op
                 existUser·p0.90:   3.285 ms/op
                 existUser·p0.95:   3.457 ms/op
                 existUser·p0.99:   4.227 ms/op
                 existUser·p0.999:  7.912 ms/op
                 existUser·p0.9999: 14.636 ms/op
                 existUser·p1.00:   14.959 ms/op

Iteration   2: 2.837 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.807 ms/op
                 existUser·p0.50:   2.843 ms/op
                 existUser·p0.90:   3.248 ms/op
                 existUser·p0.95:   3.416 ms/op
                 existUser·p0.99:   4.006 ms/op
                 existUser·p0.999:  10.675 ms/op
                 existUser·p0.9999: 13.508 ms/op
                 existUser·p1.00:   13.795 ms/op

Iteration   3: 2.851 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.759 ms/op
                 existUser·p0.50:   2.830 ms/op
                 existUser·p0.90:   3.342 ms/op
                 existUser·p0.95:   3.559 ms/op
                 existUser·p0.99:   4.383 ms/op
                 existUser·p0.999:  6.937 ms/op
                 existUser·p0.9999: 13.952 ms/op
                 existUser·p1.00:   16.384 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 337089
  mean =      2.847 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2165 
    [ 1.250,  2.500) = 49150 
    [ 2.500,  3.750) = 278507 
    [ 3.750,  5.000) = 6197 
    [ 5.000,  6.250) = 497 
    [ 6.250,  7.500) = 257 
    [ 7.500,  8.750) = 81 
    [ 8.750, 10.000) = 10 
    [10.000, 11.250) = 73 
    [11.250, 12.500) = 22 
    [12.500, 13.750) = 75 
    [13.750, 15.000) = 48 
    [15.000, 16.250) = 6 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.304 ms/op
     p(50.0000) =      2.834 ms/op
     p(90.0000) =      3.293 ms/op
     p(95.0000) =      3.478 ms/op
     p(99.0000) =      4.219 ms/op
     p(99.9000) =      7.364 ms/op
     p(99.9900) =     14.088 ms/op
     p(99.9990) =     16.192 ms/op
     p(99.9999) =     16.384 ms/op
    p(100.0000) =     16.384 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.156 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.151 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.020 ±(99.9%) 0.007 ms/op
Iteration   1: 2.960 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.791 ms/op
                 getUser·p0.50:   2.916 ms/op
                 getUser·p0.90:   3.572 ms/op
                 getUser·p0.95:   3.850 ms/op
                 getUser·p0.99:   4.661 ms/op
                 getUser·p0.999:  6.864 ms/op
                 getUser·p0.9999: 13.861 ms/op
                 getUser·p1.00:   14.270 ms/op

Iteration   2: 2.994 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.905 ms/op
                 getUser·p0.50:   2.953 ms/op
                 getUser·p0.90:   3.486 ms/op
                 getUser·p0.95:   3.674 ms/op
                 getUser·p0.99:   4.211 ms/op
                 getUser·p0.999:  6.999 ms/op
                 getUser·p0.9999: 24.649 ms/op
                 getUser·p1.00:   25.297 ms/op

Iteration   3: 3.038 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.727 ms/op
                 getUser·p0.50:   2.994 ms/op
                 getUser·p0.90:   3.576 ms/op
                 getUser·p0.95:   3.744 ms/op
                 getUser·p0.99:   4.358 ms/op
                 getUser·p0.999:  6.431 ms/op
                 getUser·p0.9999: 28.163 ms/op
                 getUser·p1.00:   28.770 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 320165
  mean =      2.997 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 29265 
    [ 2.500,  5.000) = 289724 
    [ 5.000,  7.500) = 926 
    [ 7.500, 10.000) = 58 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 87 
    [15.000, 17.500) = 38 
    [17.500, 20.000) = 3 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 10 

  Percentiles, ms/op:
      p(0.0000) =      0.727 ms/op
     p(50.0000) =      2.953 ms/op
     p(90.0000) =      3.543 ms/op
     p(95.0000) =      3.752 ms/op
     p(99.0000) =      4.440 ms/op
     p(99.9000) =      6.734 ms/op
     p(99.9900) =     27.198 ms/op
     p(99.9990) =     28.606 ms/op
     p(99.9999) =     28.770 ms/op
    p(100.0000) =     28.770 ms/op


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
# Warmup Iteration   1: 5.286 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 4.062 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.906 ±(99.9%) 0.010 ms/op
Iteration   1: 3.941 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.243 ms/op
                 listUser·p0.50:   3.760 ms/op
                 listUser·p0.90:   5.030 ms/op
                 listUser·p0.95:   5.620 ms/op
                 listUser·p0.99:   6.816 ms/op
                 listUser·p0.999:  13.688 ms/op
                 listUser·p0.9999: 16.005 ms/op
                 listUser·p1.00:   17.302 ms/op

Iteration   2: 3.888 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.794 ms/op
                 listUser·p0.50:   3.756 ms/op
                 listUser·p0.90:   4.686 ms/op
                 listUser·p0.95:   5.612 ms/op
                 listUser·p0.99:   6.636 ms/op
                 listUser·p0.999:  15.221 ms/op
                 listUser·p0.9999: 20.899 ms/op
                 listUser·p1.00:   21.234 ms/op

Iteration   3: 3.907 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.067 ms/op
                 listUser·p0.50:   3.781 ms/op
                 listUser·p0.90:   4.637 ms/op
                 listUser·p0.95:   5.579 ms/op
                 listUser·p0.99:   6.685 ms/op
                 listUser·p0.999:  14.372 ms/op
                 listUser·p0.9999: 17.643 ms/op
                 listUser·p1.00:   18.121 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 245439
  mean =      3.912 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3343 
    [ 2.500,  5.000) = 221463 
    [ 5.000,  7.500) = 19617 
    [ 7.500, 10.000) = 571 
    [10.000, 12.500) = 67 
    [12.500, 15.000) = 173 
    [15.000, 17.500) = 132 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 44 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.794 ms/op
     p(50.0000) =      3.768 ms/op
     p(90.0000) =      4.825 ms/op
     p(95.0000) =      5.603 ms/op
     p(99.0000) =      6.709 ms/op
     p(99.9000) =     14.460 ms/op
     p(99.9900) =     20.414 ms/op
     p(99.9990) =     21.153 ms/op
     p(99.9999) =     21.234 ms/op
    p(100.0000) =     21.234 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.636 ± 3.517  ops/ms
ClientGrpc.existUser                       thrpt       3  11.208 ± 3.181  ops/ms
ClientGrpc.getUser                         thrpt       3  10.671 ± 1.340  ops/ms
ClientGrpc.listUser                        thrpt       3   8.177 ± 0.502  ops/ms
ClientGrpc.createUser                       avgt       3   2.986 ± 0.164   ms/op
ClientGrpc.existUser                        avgt       3   2.866 ± 0.863   ms/op
ClientGrpc.getUser                          avgt       3   2.981 ± 0.206   ms/op
ClientGrpc.listUser                         avgt       3   3.882 ± 1.014   ms/op
ClientGrpc.createUser                     sample  319540   3.005 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.700           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.957           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.617           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.834           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.637           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.922           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.407           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          23.888           ms/op
ClientGrpc.existUser                      sample  337089   2.847 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.304           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.834           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.293           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.478           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.219           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.364           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          14.088           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          16.384           ms/op
ClientGrpc.getUser                        sample  320165   2.997 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.727           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.953           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.543           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.752           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.440           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.734           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          27.198           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          28.770           ms/op
ClientGrpc.listUser                       sample  245439   3.912 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.794           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.768           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.825           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.603           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.709           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.460           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          20.414           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          21.234           ms/op
