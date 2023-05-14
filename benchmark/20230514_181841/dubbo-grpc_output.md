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
# Warmup Iteration   1: 4.625 ops/ms
# Warmup Iteration   2: 9.201 ops/ms
# Warmup Iteration   3: 10.292 ops/ms
Iteration   1: 10.733 ops/ms
Iteration   2: 10.619 ops/ms
Iteration   3: 10.774 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.709 ±(99.9%) 1.468 ops/ms [Average]
  (min, avg, max) = (10.619, 10.709, 10.774), stdev = 0.080
  CI (99.9%): [9.241, 12.176] (assumes normal distribution)


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
# Warmup Iteration   1: 7.557 ops/ms
# Warmup Iteration   2: 10.920 ops/ms
# Warmup Iteration   3: 11.304 ops/ms
Iteration   1: 11.227 ops/ms
Iteration   2: 11.377 ops/ms
Iteration   3: 11.182 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.262 ±(99.9%) 1.866 ops/ms [Average]
  (min, avg, max) = (11.182, 11.262, 11.377), stdev = 0.102
  CI (99.9%): [9.396, 13.129] (assumes normal distribution)


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
# Warmup Iteration   1: 7.944 ops/ms
# Warmup Iteration   2: 10.308 ops/ms
# Warmup Iteration   3: 10.682 ops/ms
Iteration   1: 10.674 ops/ms
Iteration   2: 10.782 ops/ms
Iteration   3: 10.608 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.688 ±(99.9%) 1.609 ops/ms [Average]
  (min, avg, max) = (10.608, 10.688, 10.782), stdev = 0.088
  CI (99.9%): [9.079, 12.297] (assumes normal distribution)


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
# Warmup Iteration   1: 6.748 ops/ms
# Warmup Iteration   2: 7.892 ops/ms
# Warmup Iteration   3: 8.246 ops/ms
Iteration   1: 8.321 ops/ms
Iteration   2: 8.025 ops/ms
Iteration   3: 8.168 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.171 ±(99.9%) 2.699 ops/ms [Average]
  (min, avg, max) = (8.025, 8.171, 8.321), stdev = 0.148
  CI (99.9%): [5.472, 10.870] (assumes normal distribution)


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
# Warmup Iteration   1: 4.167 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.124 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.030 ±(99.9%) 0.003 ms/op
Iteration   1: 2.929 ±(99.9%) 0.004 ms/op
Iteration   2: 2.971 ±(99.9%) 0.003 ms/op
Iteration   3: 2.938 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.946 ±(99.9%) 0.396 ms/op [Average]
  (min, avg, max) = (2.929, 2.946, 2.971), stdev = 0.022
  CI (99.9%): [2.550, 3.343] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 4.217 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.000 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.817 ±(99.9%) 0.003 ms/op
Iteration   1: 2.868 ±(99.9%) 0.003 ms/op
Iteration   2: 2.788 ±(99.9%) 0.003 ms/op
Iteration   3: 2.932 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.862 ±(99.9%) 1.317 ms/op [Average]
  (min, avg, max) = (2.788, 2.862, 2.932), stdev = 0.072
  CI (99.9%): [1.546, 4.179] (assumes normal distribution)


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
# Warmup Iteration   1: 4.156 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.046 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.972 ±(99.9%) 0.003 ms/op
Iteration   1: 2.965 ±(99.9%) 0.002 ms/op
Iteration   2: 3.044 ±(99.9%) 0.002 ms/op
Iteration   3: 3.048 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.019 ±(99.9%) 0.850 ms/op [Average]
  (min, avg, max) = (2.965, 3.019, 3.048), stdev = 0.047
  CI (99.9%): [2.169, 3.869] (assumes normal distribution)


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
# Warmup Iteration   1: 4.793 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 4.277 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.899 ±(99.9%) 0.014 ms/op
Iteration   1: 3.924 ±(99.9%) 0.033 ms/op
Iteration   2: 3.906 ±(99.9%) 0.012 ms/op
Iteration   3: 3.937 ±(99.9%) 0.028 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.922 ±(99.9%) 0.279 ms/op [Average]
  (min, avg, max) = (3.906, 3.922, 3.937), stdev = 0.015
  CI (99.9%): [3.643, 4.201] (assumes normal distribution)


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
# Warmup Iteration   1: 4.535 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.360 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.011 ±(99.9%) 0.007 ms/op
Iteration   1: 3.017 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.803 ms/op
                 createUser·p0.50:   2.990 ms/op
                 createUser·p0.90:   3.577 ms/op
                 createUser·p0.95:   3.781 ms/op
                 createUser·p0.99:   4.497 ms/op
                 createUser·p0.999:  9.109 ms/op
                 createUser·p0.9999: 17.282 ms/op
                 createUser·p1.00:   18.743 ms/op

Iteration   2: 2.982 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.797 ms/op
                 createUser·p0.50:   2.974 ms/op
                 createUser·p0.90:   3.478 ms/op
                 createUser·p0.95:   3.703 ms/op
                 createUser·p0.99:   4.243 ms/op
                 createUser·p0.999:  8.516 ms/op
                 createUser·p0.9999: 13.222 ms/op
                 createUser·p1.00:   13.713 ms/op

Iteration   3: 2.996 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.582 ms/op
                 createUser·p0.50:   2.990 ms/op
                 createUser·p0.90:   3.572 ms/op
                 createUser·p0.95:   3.744 ms/op
                 createUser·p0.99:   4.415 ms/op
                 createUser·p0.999:  6.342 ms/op
                 createUser·p0.9999: 29.108 ms/op
                 createUser·p1.00:   29.229 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 320165
  mean =      2.998 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 29589 
    [ 2.500,  5.000) = 289164 
    [ 5.000,  7.500) = 1043 
    [ 7.500, 10.000) = 143 
    [10.000, 12.500) = 61 
    [12.500, 15.000) = 77 
    [15.000, 17.500) = 51 
    [17.500, 20.000) = 5 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.582 ms/op
     p(50.0000) =      2.982 ms/op
     p(90.0000) =      3.547 ms/op
     p(95.0000) =      3.744 ms/op
     p(99.0000) =      4.399 ms/op
     p(99.9000) =      8.312 ms/op
     p(99.9900) =     28.539 ms/op
     p(99.9990) =     29.196 ms/op
     p(99.9999) =     29.229 ms/op
    p(100.0000) =     29.229 ms/op


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
# Warmup Iteration   1: 4.293 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.164 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.867 ±(99.9%) 0.006 ms/op
Iteration   1: 2.848 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.664 ms/op
                 existUser·p0.50:   2.859 ms/op
                 existUser·p0.90:   3.269 ms/op
                 existUser·p0.95:   3.453 ms/op
                 existUser·p0.99:   4.358 ms/op
                 existUser·p0.999:  6.662 ms/op
                 existUser·p0.9999: 13.129 ms/op
                 existUser·p1.00:   13.500 ms/op

Iteration   2: 2.865 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.588 ms/op
                 existUser·p0.50:   2.863 ms/op
                 existUser·p0.90:   3.318 ms/op
                 existUser·p0.95:   3.531 ms/op
                 existUser·p0.99:   4.354 ms/op
                 existUser·p0.999:  5.934 ms/op
                 existUser·p0.9999: 13.247 ms/op
                 existUser·p1.00:   13.779 ms/op

Iteration   3: 2.880 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.504 ms/op
                 existUser·p0.50:   2.855 ms/op
                 existUser·p0.90:   3.318 ms/op
                 existUser·p0.95:   3.650 ms/op
                 existUser·p0.99:   4.489 ms/op
                 existUser·p0.999:  9.863 ms/op
                 existUser·p0.9999: 25.788 ms/op
                 existUser·p1.00:   26.608 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 335063
  mean =      2.864 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 44188 
    [ 2.500,  5.000) = 289881 
    [ 5.000,  7.500) = 736 
    [ 7.500, 10.000) = 61 
    [10.000, 12.500) = 45 
    [12.500, 15.000) = 119 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 22 

  Percentiles, ms/op:
      p(0.0000) =      0.504 ms/op
     p(50.0000) =      2.859 ms/op
     p(90.0000) =      3.297 ms/op
     p(95.0000) =      3.547 ms/op
     p(99.0000) =      4.415 ms/op
     p(99.9000) =      6.644 ms/op
     p(99.9900) =     15.060 ms/op
     p(99.9990) =     26.498 ms/op
     p(99.9999) =     26.608 ms/op
    p(100.0000) =     26.608 ms/op


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
# Warmup Iteration   1: 4.372 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.396 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 2.999 ±(99.9%) 0.007 ms/op
Iteration   1: 2.943 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.703 ms/op
                 getUser·p0.50:   2.945 ms/op
                 getUser·p0.90:   3.400 ms/op
                 getUser·p0.95:   3.678 ms/op
                 getUser·p0.99:   4.383 ms/op
                 getUser·p0.999:  8.137 ms/op
                 getUser·p0.9999: 14.279 ms/op
                 getUser·p1.00:   14.795 ms/op

Iteration   2: 2.991 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.479 ms/op
                 getUser·p0.50:   2.990 ms/op
                 getUser·p0.90:   3.650 ms/op
                 getUser·p0.95:   3.863 ms/op
                 getUser·p0.99:   4.555 ms/op
                 getUser·p0.999:  7.815 ms/op
                 getUser·p0.9999: 13.910 ms/op
                 getUser·p1.00:   14.909 ms/op

Iteration   3: 2.952 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.642 ms/op
                 getUser·p0.50:   2.978 ms/op
                 getUser·p0.90:   3.420 ms/op
                 getUser·p0.95:   3.772 ms/op
                 getUser·p0.99:   4.391 ms/op
                 getUser·p0.999:  6.177 ms/op
                 getUser·p0.9999: 17.203 ms/op
                 getUser·p1.00:   17.367 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 323996
  mean =      2.962 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2596 
    [ 1.250,  2.500) = 32951 
    [ 2.500,  3.750) = 270205 
    [ 3.750,  5.000) = 16982 
    [ 5.000,  6.250) = 694 
    [ 6.250,  7.500) = 244 
    [ 7.500,  8.750) = 100 
    [ 8.750, 10.000) = 6 
    [10.000, 11.250) = 31 
    [11.250, 12.500) = 4 
    [12.500, 13.750) = 74 
    [13.750, 15.000) = 71 
    [15.000, 16.250) = 6 
    [16.250, 17.500) = 32 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.479 ms/op
     p(50.0000) =      2.970 ms/op
     p(90.0000) =      3.506 ms/op
     p(95.0000) =      3.797 ms/op
     p(99.0000) =      4.432 ms/op
     p(99.9000) =      7.504 ms/op
     p(99.9900) =     16.325 ms/op
     p(99.9990) =     17.302 ms/op
     p(99.9999) =     17.367 ms/op
    p(100.0000) =     17.367 ms/op


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
# Warmup Iteration   1: 5.313 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 4.336 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.925 ±(99.9%) 0.011 ms/op
Iteration   1: 3.846 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.452 ms/op
                 listUser·p0.50:   3.752 ms/op
                 listUser·p0.90:   4.407 ms/op
                 listUser·p0.95:   5.071 ms/op
                 listUser·p0.99:   6.521 ms/op
                 listUser·p0.999:  14.151 ms/op
                 listUser·p0.9999: 18.166 ms/op
                 listUser·p1.00:   18.579 ms/op

Iteration   2: 3.899 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.329 ms/op
                 listUser·p0.50:   3.764 ms/op
                 listUser·p0.90:   4.858 ms/op
                 listUser·p0.95:   5.587 ms/op
                 listUser·p0.99:   6.783 ms/op
                 listUser·p0.999:  12.659 ms/op
                 listUser·p0.9999: 14.808 ms/op
                 listUser·p1.00:   18.350 ms/op

Iteration   3: 3.954 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.876 ms/op
                 listUser·p0.50:   3.801 ms/op
                 listUser·p0.90:   5.005 ms/op
                 listUser·p0.95:   5.530 ms/op
                 listUser·p0.99:   6.873 ms/op
                 listUser·p0.999:  16.144 ms/op
                 listUser·p0.9999: 20.444 ms/op
                 listUser·p1.00:   23.233 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 246427
  mean =      3.899 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4591 
    [ 2.500,  5.000) = 222162 
    [ 5.000,  7.500) = 18574 
    [ 7.500, 10.000) = 623 
    [10.000, 12.500) = 110 
    [12.500, 15.000) = 181 
    [15.000, 17.500) = 90 
    [17.500, 20.000) = 80 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.876 ms/op
     p(50.0000) =      3.768 ms/op
     p(90.0000) =      4.792 ms/op
     p(95.0000) =      5.431 ms/op
     p(99.0000) =      6.717 ms/op
     p(99.9000) =     13.959 ms/op
     p(99.9900) =     19.488 ms/op
     p(99.9990) =     23.080 ms/op
     p(99.9999) =     23.233 ms/op
    p(100.0000) =     23.233 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.709 ± 1.468  ops/ms
ClientGrpc.existUser                       thrpt       3  11.262 ± 1.866  ops/ms
ClientGrpc.getUser                         thrpt       3  10.688 ± 1.609  ops/ms
ClientGrpc.listUser                        thrpt       3   8.171 ± 2.699  ops/ms
ClientGrpc.createUser                       avgt       3   2.946 ± 0.396   ms/op
ClientGrpc.existUser                        avgt       3   2.862 ± 1.317   ms/op
ClientGrpc.getUser                          avgt       3   3.019 ± 0.850   ms/op
ClientGrpc.listUser                         avgt       3   3.922 ± 0.279   ms/op
ClientGrpc.createUser                     sample  320165   2.998 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.582           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.982           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.547           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.744           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.399           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.312           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          28.539           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          29.229           ms/op
ClientGrpc.existUser                      sample  335063   2.864 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.504           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.859           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.297           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.547           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.415           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.644           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          15.060           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          26.608           ms/op
ClientGrpc.getUser                        sample  323996   2.962 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.479           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.970           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.506           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.797           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.432           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.504           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          16.325           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          17.367           ms/op
ClientGrpc.listUser                       sample  246427   3.899 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.876           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.768           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.792           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.431           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.717           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.959           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          19.488           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          23.233           ms/op
