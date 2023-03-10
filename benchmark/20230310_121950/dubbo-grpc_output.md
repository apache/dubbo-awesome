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
# Warmup Iteration   1: 4.719 ops/ms
# Warmup Iteration   2: 9.650 ops/ms
# Warmup Iteration   3: 10.390 ops/ms
Iteration   1: 10.684 ops/ms
Iteration   2: 10.731 ops/ms
Iteration   3: 10.948 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.788 ±(99.9%) 2.569 ops/ms [Average]
  (min, avg, max) = (10.684, 10.788, 10.948), stdev = 0.141
  CI (99.9%): [8.218, 13.357] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 8.629 ops/ms
# Warmup Iteration   2: 11.056 ops/ms
# Warmup Iteration   3: 11.310 ops/ms
Iteration   1: 11.227 ops/ms
Iteration   2: 11.160 ops/ms
Iteration   3: 11.156 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.181 ±(99.9%) 0.731 ops/ms [Average]
  (min, avg, max) = (11.156, 11.181, 11.227), stdev = 0.040
  CI (99.9%): [10.450, 11.912] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.259 ops/ms
# Warmup Iteration   2: 10.405 ops/ms
# Warmup Iteration   3: 10.742 ops/ms
Iteration   1: 10.755 ops/ms
Iteration   2: 10.910 ops/ms
Iteration   3: 10.728 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.798 ±(99.9%) 1.796 ops/ms [Average]
  (min, avg, max) = (10.728, 10.798, 10.910), stdev = 0.098
  CI (99.9%): [9.002, 12.594] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 5.764 ops/ms
# Warmup Iteration   2: 8.070 ops/ms
# Warmup Iteration   3: 8.255 ops/ms
Iteration   1: 8.377 ops/ms
Iteration   2: 8.353 ops/ms
Iteration   3: 8.357 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.363 ±(99.9%) 0.237 ops/ms [Average]
  (min, avg, max) = (8.353, 8.363, 8.377), stdev = 0.013
  CI (99.9%): [8.125, 8.600] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 3.875 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.072 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.992 ±(99.9%) 0.003 ms/op
Iteration   1: 3.000 ±(99.9%) 0.007 ms/op
Iteration   2: 2.937 ±(99.9%) 0.002 ms/op
Iteration   3: 2.986 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.974 ±(99.9%) 0.604 ms/op [Average]
  (min, avg, max) = (2.937, 2.974, 3.000), stdev = 0.033
  CI (99.9%): [2.371, 3.578] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.868 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.906 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.866 ±(99.9%) 0.004 ms/op
Iteration   1: 2.846 ±(99.9%) 0.005 ms/op
Iteration   2: 2.808 ±(99.9%) 0.004 ms/op
Iteration   3: 2.799 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.818 ±(99.9%) 0.460 ms/op [Average]
  (min, avg, max) = (2.799, 2.818, 2.846), stdev = 0.025
  CI (99.9%): [2.358, 3.278] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 3.892 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.109 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.993 ±(99.9%) 0.002 ms/op
Iteration   1: 2.947 ±(99.9%) 0.002 ms/op
Iteration   2: 2.979 ±(99.9%) 0.003 ms/op
Iteration   3: 2.952 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.959 ±(99.9%) 0.312 ms/op [Average]
  (min, avg, max) = (2.947, 2.959, 2.979), stdev = 0.017
  CI (99.9%): [2.648, 3.271] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 4.756 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.902 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.806 ±(99.9%) 0.010 ms/op
Iteration   1: 3.860 ±(99.9%) 0.008 ms/op
Iteration   2: 3.733 ±(99.9%) 0.006 ms/op
Iteration   3: 3.868 ±(99.9%) 0.027 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.820 ±(99.9%) 1.380 ms/op [Average]
  (min, avg, max) = (3.733, 3.820, 3.868), stdev = 0.076
  CI (99.9%): [2.440, 5.201] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 3.959 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.086 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.001 ±(99.9%) 0.006 ms/op
Iteration   1: 2.946 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.751 ms/op
                 createUser·p0.50:   2.945 ms/op
                 createUser·p0.90:   3.310 ms/op
                 createUser·p0.95:   3.457 ms/op
                 createUser·p0.99:   4.219 ms/op
                 createUser·p0.999:  7.908 ms/op
                 createUser·p0.9999: 11.583 ms/op
                 createUser·p1.00:   11.960 ms/op

Iteration   2: 2.953 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.556 ms/op
                 createUser·p0.50:   2.949 ms/op
                 createUser·p0.90:   3.437 ms/op
                 createUser·p0.95:   3.670 ms/op
                 createUser·p0.99:   4.399 ms/op
                 createUser·p0.999:  6.867 ms/op
                 createUser·p0.9999: 13.728 ms/op
                 createUser·p1.00:   14.975 ms/op

Iteration   3: 2.956 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.817 ms/op
                 createUser·p0.50:   2.966 ms/op
                 createUser·p0.90:   3.514 ms/op
                 createUser·p0.95:   3.678 ms/op
                 createUser·p0.99:   4.309 ms/op
                 createUser·p0.999:  7.441 ms/op
                 createUser·p0.9999: 16.332 ms/op
                 createUser·p1.00:   17.695 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 325317
  mean =      2.952 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1937 
    [ 1.250,  2.500) = 28656 
    [ 2.500,  3.750) = 283955 
    [ 3.750,  5.000) = 9585 
    [ 5.000,  6.250) = 614 
    [ 6.250,  7.500) = 245 
    [ 7.500,  8.750) = 69 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 50 
    [11.250, 12.500) = 46 
    [12.500, 13.750) = 82 
    [13.750, 15.000) = 61 
    [15.000, 16.250) = 6 
    [16.250, 17.500) = 4 
    [17.500, 18.750) = 7 

  Percentiles, ms/op:
      p(0.0000) =      0.556 ms/op
     p(50.0000) =      2.953 ms/op
     p(90.0000) =      3.424 ms/op
     p(95.0000) =      3.629 ms/op
     p(99.0000) =      4.317 ms/op
     p(99.9000) =      7.507 ms/op
     p(99.9900) =     14.786 ms/op
     p(99.9990) =     17.621 ms/op
     p(99.9999) =     17.695 ms/op
    p(100.0000) =     17.695 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.766 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 2.961 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.898 ±(99.9%) 0.005 ms/op
Iteration   1: 2.907 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.625 ms/op
                 existUser·p0.50:   2.875 ms/op
                 existUser·p0.90:   3.473 ms/op
                 existUser·p0.95:   3.699 ms/op
                 existUser·p0.99:   4.596 ms/op
                 existUser·p0.999:  7.520 ms/op
                 existUser·p0.9999: 10.223 ms/op
                 existUser·p1.00:   10.764 ms/op

Iteration   2: 2.889 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.722 ms/op
                 existUser·p0.50:   2.863 ms/op
                 existUser·p0.90:   3.359 ms/op
                 existUser·p0.95:   3.568 ms/op
                 existUser·p0.99:   4.264 ms/op
                 existUser·p0.999:  6.382 ms/op
                 existUser·p0.9999: 15.121 ms/op
                 existUser·p1.00:   15.565 ms/op

Iteration   3: 2.891 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.778 ms/op
                 existUser·p0.50:   2.855 ms/op
                 existUser·p0.90:   3.277 ms/op
                 existUser·p0.95:   3.547 ms/op
                 existUser·p0.99:   4.152 ms/op
                 existUser·p0.999:  10.326 ms/op
                 existUser·p0.9999: 15.249 ms/op
                 existUser·p1.00:   15.696 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 331548
  mean =      2.896 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1676 
    [ 1.250,  2.500) = 39856 
    [ 2.500,  3.750) = 279870 
    [ 3.750,  5.000) = 8731 
    [ 5.000,  6.250) = 795 
    [ 6.250,  7.500) = 318 
    [ 7.500,  8.750) = 42 
    [ 8.750, 10.000) = 68 
    [10.000, 11.250) = 96 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 31 
    [15.000, 16.250) = 33 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.625 ms/op
     p(50.0000) =      2.863 ms/op
     p(90.0000) =      3.383 ms/op
     p(95.0000) =      3.609 ms/op
     p(99.0000) =      4.391 ms/op
     p(99.9000) =      7.327 ms/op
     p(99.9900) =     15.019 ms/op
     p(99.9990) =     15.587 ms/op
     p(99.9999) =     15.696 ms/op
    p(100.0000) =     15.696 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 3.822 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.084 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.015 ±(99.9%) 0.006 ms/op
Iteration   1: 2.992 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.674 ms/op
                 getUser·p0.50:   2.978 ms/op
                 getUser·p0.90:   3.482 ms/op
                 getUser·p0.95:   3.754 ms/op
                 getUser·p0.99:   4.391 ms/op
                 getUser·p0.999:  6.490 ms/op
                 getUser·p0.9999: 13.943 ms/op
                 getUser·p1.00:   14.320 ms/op

Iteration   2: 2.975 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.554 ms/op
                 getUser·p0.50:   2.957 ms/op
                 getUser·p0.90:   3.498 ms/op
                 getUser·p0.95:   3.715 ms/op
                 getUser·p0.99:   4.334 ms/op
                 getUser·p0.999:  6.702 ms/op
                 getUser·p0.9999: 13.214 ms/op
                 getUser·p1.00:   13.550 ms/op

Iteration   3: 2.988 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.887 ms/op
                 getUser·p0.50:   2.986 ms/op
                 getUser·p0.90:   3.400 ms/op
                 getUser·p0.95:   3.596 ms/op
                 getUser·p0.99:   4.157 ms/op
                 getUser·p0.999:  7.928 ms/op
                 getUser·p0.9999: 14.737 ms/op
                 getUser·p1.00:   15.778 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 321472
  mean =      2.985 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1172 
    [ 1.250,  2.500) = 22712 
    [ 2.500,  3.750) = 283831 
    [ 3.750,  5.000) = 12751 
    [ 5.000,  6.250) = 535 
    [ 6.250,  7.500) = 146 
    [ 7.500,  8.750) = 108 
    [ 8.750, 10.000) = 56 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 41 
    [13.750, 15.000) = 80 
    [15.000, 16.250) = 7 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.554 ms/op
     p(50.0000) =      2.974 ms/op
     p(90.0000) =      3.453 ms/op
     p(95.0000) =      3.703 ms/op
     p(99.0000) =      4.293 ms/op
     p(99.9000) =      7.545 ms/op
     p(99.9900) =     14.483 ms/op
     p(99.9990) =     15.669 ms/op
     p(99.9999) =     15.778 ms/op
    p(100.0000) =     15.778 ms/op


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
# Warmup Iteration   1: 4.697 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.924 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.969 ±(99.9%) 0.012 ms/op
Iteration   1: 3.786 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.856 ms/op
                 listUser·p0.50:   3.662 ms/op
                 listUser·p0.90:   4.784 ms/op
                 listUser·p0.95:   5.439 ms/op
                 listUser·p0.99:   6.716 ms/op
                 listUser·p0.999:  12.966 ms/op
                 listUser·p0.9999: 13.911 ms/op
                 listUser·p1.00:   15.155 ms/op

Iteration   2: 3.836 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.901 ms/op
                 listUser·p0.50:   3.723 ms/op
                 listUser·p0.90:   4.473 ms/op
                 listUser·p0.95:   5.145 ms/op
                 listUser·p0.99:   6.536 ms/op
                 listUser·p0.999:  15.811 ms/op
                 listUser·p0.9999: 28.801 ms/op
                 listUser·p1.00:   29.327 ms/op

Iteration   3: 3.851 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.090 ms/op
                 listUser·p0.50:   3.690 ms/op
                 listUser·p0.90:   4.948 ms/op
                 listUser·p0.95:   5.497 ms/op
                 listUser·p0.99:   6.676 ms/op
                 listUser·p0.999:  14.284 ms/op
                 listUser·p0.9999: 22.381 ms/op
                 listUser·p1.00:   23.003 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 251330
  mean =      3.824 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5153 
    [ 2.500,  5.000) = 226776 
    [ 5.000,  7.500) = 18302 
    [ 7.500, 10.000) = 621 
    [10.000, 12.500) = 102 
    [12.500, 15.000) = 200 
    [15.000, 17.500) = 79 
    [17.500, 20.000) = 4 
    [20.000, 22.500) = 62 
    [22.500, 25.000) = 12 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.856 ms/op
     p(50.0000) =      3.695 ms/op
     p(90.0000) =      4.776 ms/op
     p(95.0000) =      5.390 ms/op
     p(99.0000) =      6.644 ms/op
     p(99.9000) =     13.686 ms/op
     p(99.9900) =     22.573 ms/op
     p(99.9990) =     29.130 ms/op
     p(99.9999) =     29.327 ms/op
    p(100.0000) =     29.327 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.788 ± 2.569  ops/ms
ClientGrpc.existUser                       thrpt       3  11.181 ± 0.731  ops/ms
ClientGrpc.getUser                         thrpt       3  10.798 ± 1.796  ops/ms
ClientGrpc.listUser                        thrpt       3   8.363 ± 0.237  ops/ms
ClientGrpc.createUser                       avgt       3   2.974 ± 0.604   ms/op
ClientGrpc.existUser                        avgt       3   2.818 ± 0.460   ms/op
ClientGrpc.getUser                          avgt       3   2.959 ± 0.312   ms/op
ClientGrpc.listUser                         avgt       3   3.820 ± 1.380   ms/op
ClientGrpc.createUser                     sample  325317   2.952 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.556           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.953           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.424           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.629           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.317           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.507           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          14.786           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          17.695           ms/op
ClientGrpc.existUser                      sample  331548   2.896 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.625           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.863           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.383           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.609           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.391           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.327           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          15.019           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          15.696           ms/op
ClientGrpc.getUser                        sample  321472   2.985 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.554           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.974           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.453           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.703           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.293           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.545           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          14.483           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          15.778           ms/op
ClientGrpc.listUser                       sample  251330   3.824 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.856           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.695           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.776           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.390           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.644           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.686           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.573           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          29.327           ms/op
