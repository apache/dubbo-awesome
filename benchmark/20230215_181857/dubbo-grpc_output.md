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
# Warmup Iteration   1: 4.991 ops/ms
# Warmup Iteration   2: 9.312 ops/ms
# Warmup Iteration   3: 10.484 ops/ms
Iteration   1: 10.952 ops/ms
Iteration   2: 10.067 ops/ms
Iteration   3: 10.160 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.393 ±(99.9%) 8.878 ops/ms [Average]
  (min, avg, max) = (10.067, 10.393, 10.952), stdev = 0.487
  CI (99.9%): [1.515, 19.271] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 8.106 ops/ms
# Warmup Iteration   2: 10.591 ops/ms
# Warmup Iteration   3: 11.365 ops/ms
Iteration   1: 10.835 ops/ms
Iteration   2: 10.995 ops/ms
Iteration   3: 11.011 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.947 ±(99.9%) 1.774 ops/ms [Average]
  (min, avg, max) = (10.835, 10.947, 11.011), stdev = 0.097
  CI (99.9%): [9.173, 12.720] (assumes normal distribution)


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
# Warmup Iteration   1: 7.681 ops/ms
# Warmup Iteration   2: 10.093 ops/ms
# Warmup Iteration   3: 10.675 ops/ms
Iteration   1: 10.596 ops/ms
Iteration   2: 10.401 ops/ms
Iteration   3: 10.593 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.530 ±(99.9%) 2.038 ops/ms [Average]
  (min, avg, max) = (10.401, 10.530, 10.596), stdev = 0.112
  CI (99.9%): [8.492, 12.568] (assumes normal distribution)


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
# Warmup Iteration   1: 6.196 ops/ms
# Warmup Iteration   2: 7.902 ops/ms
# Warmup Iteration   3: 8.092 ops/ms
Iteration   1: 7.885 ops/ms
Iteration   2: 8.116 ops/ms
Iteration   3: 8.117 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.040 ±(99.9%) 2.437 ops/ms [Average]
  (min, avg, max) = (7.885, 8.040, 8.117), stdev = 0.134
  CI (99.9%): [5.602, 10.477] (assumes normal distribution)


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
# Warmup Iteration   1: 4.040 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.044 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.068 ±(99.9%) 0.003 ms/op
Iteration   1: 2.977 ±(99.9%) 0.003 ms/op
Iteration   2: 3.083 ±(99.9%) 0.003 ms/op
Iteration   3: 2.956 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.005 ±(99.9%) 1.241 ms/op [Average]
  (min, avg, max) = (2.956, 3.005, 3.083), stdev = 0.068
  CI (99.9%): [1.765, 4.246] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.601 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.979 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.908 ±(99.9%) 0.003 ms/op
Iteration   1: 2.931 ±(99.9%) 0.002 ms/op
Iteration   2: 2.852 ±(99.9%) 0.003 ms/op
Iteration   3: 2.997 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.926 ±(99.9%) 1.324 ms/op [Average]
  (min, avg, max) = (2.852, 2.926, 2.997), stdev = 0.073
  CI (99.9%): [1.602, 4.251] (assumes normal distribution)


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
# Warmup Iteration   1: 3.929 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.118 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.002 ±(99.9%) 0.002 ms/op
Iteration   1: 2.991 ±(99.9%) 0.004 ms/op
Iteration   2: 3.040 ±(99.9%) 0.002 ms/op
Iteration   3: 2.963 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.998 ±(99.9%) 0.717 ms/op [Average]
  (min, avg, max) = (2.963, 2.998, 3.040), stdev = 0.039
  CI (99.9%): [2.281, 3.715] (assumes normal distribution)


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
# Warmup Iteration   1: 4.574 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 4.110 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.957 ±(99.9%) 0.059 ms/op
Iteration   1: 3.879 ±(99.9%) 0.045 ms/op
Iteration   2: 3.981 ±(99.9%) 0.025 ms/op
Iteration   3: 4.002 ±(99.9%) 0.033 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.954 ±(99.9%) 1.204 ms/op [Average]
  (min, avg, max) = (3.879, 3.954, 4.002), stdev = 0.066
  CI (99.9%): [2.750, 5.158] (assumes normal distribution)


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
# Warmup Iteration   1: 3.894 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.101 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.042 ±(99.9%) 0.006 ms/op
Iteration   1: 2.983 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.345 ms/op
                 createUser·p0.50:   2.986 ms/op
                 createUser·p0.90:   3.527 ms/op
                 createUser·p0.95:   3.760 ms/op
                 createUser·p0.99:   4.383 ms/op
                 createUser·p0.999:  9.820 ms/op
                 createUser·p0.9999: 15.471 ms/op
                 createUser·p1.00:   15.663 ms/op

Iteration   2: 3.062 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.938 ms/op
                 createUser·p0.50:   3.047 ms/op
                 createUser·p0.90:   3.682 ms/op
                 createUser·p0.95:   3.875 ms/op
                 createUser·p0.99:   4.219 ms/op
                 createUser·p0.999:  8.913 ms/op
                 createUser·p0.9999: 13.420 ms/op
                 createUser·p1.00:   14.434 ms/op

Iteration   3: 3.153 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.635 ms/op
                 createUser·p0.50:   3.142 ms/op
                 createUser·p0.90:   3.822 ms/op
                 createUser·p0.95:   3.957 ms/op
                 createUser·p0.99:   4.268 ms/op
                 createUser·p0.999:  8.957 ms/op
                 createUser·p0.9999: 19.689 ms/op
                 createUser·p1.00:   19.890 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 313068
  mean =      3.065 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1556 
    [ 1.250,  2.500) = 30905 
    [ 2.500,  3.750) = 253232 
    [ 3.750,  5.000) = 26127 
    [ 5.000,  6.250) = 565 
    [ 6.250,  7.500) = 252 
    [ 7.500,  8.750) = 88 
    [ 8.750, 10.000) = 47 
    [10.000, 11.250) = 55 
    [11.250, 12.500) = 58 
    [12.500, 13.750) = 58 
    [13.750, 15.000) = 56 
    [15.000, 16.250) = 35 
    [16.250, 17.500) = 2 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.345 ms/op
     p(50.0000) =      3.047 ms/op
     p(90.0000) =      3.711 ms/op
     p(95.0000) =      3.891 ms/op
     p(99.0000) =      4.276 ms/op
     p(99.9000) =      8.962 ms/op
     p(99.9900) =     19.318 ms/op
     p(99.9990) =     19.759 ms/op
     p(99.9999) =     19.890 ms/op
    p(100.0000) =     19.890 ms/op


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
# Warmup Iteration   1: 3.682 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.043 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.947 ±(99.9%) 0.006 ms/op
Iteration   1: 2.856 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.650 ms/op
                 existUser·p0.50:   2.855 ms/op
                 existUser·p0.90:   3.428 ms/op
                 existUser·p0.95:   3.650 ms/op
                 existUser·p0.99:   4.157 ms/op
                 existUser·p0.999:  6.005 ms/op
                 existUser·p0.9999: 17.367 ms/op
                 existUser·p1.00:   17.629 ms/op

Iteration   2: 2.950 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.495 ms/op
                 existUser·p0.50:   2.941 ms/op
                 existUser·p0.90:   3.539 ms/op
                 existUser·p0.95:   3.695 ms/op
                 existUser·p0.99:   4.055 ms/op
                 existUser·p0.999:  6.174 ms/op
                 existUser·p0.9999: 13.719 ms/op
                 existUser·p1.00:   14.139 ms/op

Iteration   3: 2.900 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.666 ms/op
                 existUser·p0.50:   2.908 ms/op
                 existUser·p0.90:   3.510 ms/op
                 existUser·p0.95:   3.674 ms/op
                 existUser·p0.99:   4.080 ms/op
                 existUser·p0.999:  10.289 ms/op
                 existUser·p0.9999: 14.024 ms/op
                 existUser·p1.00:   14.860 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 330668
  mean =      2.901 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 3487 
    [ 1.250,  2.500) = 52281 
    [ 2.500,  3.750) = 263158 
    [ 3.750,  5.000) = 10813 
    [ 5.000,  6.250) = 443 
    [ 6.250,  7.500) = 171 
    [ 7.500,  8.750) = 28 
    [ 8.750, 10.000) = 49 
    [10.000, 11.250) = 101 
    [11.250, 12.500) = 13 
    [12.500, 13.750) = 65 
    [13.750, 15.000) = 27 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 29 
    [17.500, 18.750) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.495 ms/op
     p(50.0000) =      2.896 ms/op
     p(90.0000) =      3.498 ms/op
     p(95.0000) =      3.674 ms/op
     p(99.0000) =      4.100 ms/op
     p(99.9000) =      7.430 ms/op
     p(99.9900) =     14.830 ms/op
     p(99.9990) =     17.544 ms/op
     p(99.9999) =     17.629 ms/op
    p(100.0000) =     17.629 ms/op


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
# Warmup Iteration   1: 3.885 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.160 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.138 ±(99.9%) 0.007 ms/op
Iteration   1: 3.061 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.723 ms/op
                 getUser·p0.50:   3.056 ms/op
                 getUser·p0.90:   3.674 ms/op
                 getUser·p0.95:   3.838 ms/op
                 getUser·p0.99:   4.186 ms/op
                 getUser·p0.999:  6.347 ms/op
                 getUser·p0.9999: 25.625 ms/op
                 getUser·p1.00:   25.919 ms/op

Iteration   2: 3.120 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.546 ms/op
                 getUser·p0.50:   3.088 ms/op
                 getUser·p0.90:   3.793 ms/op
                 getUser·p0.95:   3.977 ms/op
                 getUser·p0.99:   4.276 ms/op
                 getUser·p0.999:  7.631 ms/op
                 getUser·p0.9999: 13.164 ms/op
                 getUser·p1.00:   13.681 ms/op

Iteration   3: 3.021 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.652 ms/op
                 getUser·p0.50:   3.031 ms/op
                 getUser·p0.90:   3.699 ms/op
                 getUser·p0.95:   3.899 ms/op
                 getUser·p0.99:   4.293 ms/op
                 getUser·p0.999:  6.860 ms/op
                 getUser·p0.9999: 15.152 ms/op
                 getUser·p1.00:   15.516 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 312997
  mean =      3.067 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 28858 
    [ 2.500,  5.000) = 283218 
    [ 5.000,  7.500) = 678 
    [ 7.500, 10.000) = 71 
    [10.000, 12.500) = 47 
    [12.500, 15.000) = 71 
    [15.000, 17.500) = 22 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 31 

  Percentiles, ms/op:
      p(0.0000) =      0.546 ms/op
     p(50.0000) =      3.056 ms/op
     p(90.0000) =      3.719 ms/op
     p(95.0000) =      3.908 ms/op
     p(99.0000) =      4.260 ms/op
     p(99.9000) =      6.889 ms/op
     p(99.9900) =     24.976 ms/op
     p(99.9990) =     25.788 ms/op
     p(99.9999) =     25.919 ms/op
    p(100.0000) =     25.919 ms/op


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
# Warmup Iteration   1: 4.936 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 4.063 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.976 ±(99.9%) 0.010 ms/op
Iteration   1: 3.866 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.194 ms/op
                 listUser·p0.50:   3.740 ms/op
                 listUser·p0.90:   4.719 ms/op
                 listUser·p0.95:   5.505 ms/op
                 listUser·p0.99:   6.480 ms/op
                 listUser·p0.999:  13.602 ms/op
                 listUser·p0.9999: 19.422 ms/op
                 listUser·p1.00:   19.988 ms/op

Iteration   2: 3.917 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.171 ms/op
                 listUser·p0.50:   3.772 ms/op
                 listUser·p0.90:   4.792 ms/op
                 listUser·p0.95:   5.489 ms/op
                 listUser·p0.99:   6.693 ms/op
                 listUser·p0.999:  13.005 ms/op
                 listUser·p0.9999: 19.050 ms/op
                 listUser·p1.00:   20.677 ms/op

Iteration   3: 3.966 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.317 ms/op
                 listUser·p0.50:   3.842 ms/op
                 listUser·p0.90:   4.743 ms/op
                 listUser·p0.95:   5.325 ms/op
                 listUser·p0.99:   6.530 ms/op
                 listUser·p0.999:  13.259 ms/op
                 listUser·p0.9999: 20.281 ms/op
                 listUser·p1.00:   20.840 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 245024
  mean =      3.916 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3161 
    [ 2.500,  5.000) = 223248 
    [ 5.000,  7.500) = 17627 
    [ 7.500, 10.000) = 536 
    [10.000, 12.500) = 129 
    [12.500, 15.000) = 118 
    [15.000, 17.500) = 53 
    [17.500, 20.000) = 136 
    [20.000, 22.500) = 16 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.171 ms/op
     p(50.0000) =      3.789 ms/op
     p(90.0000) =      4.751 ms/op
     p(95.0000) =      5.431 ms/op
     p(99.0000) =      6.562 ms/op
     p(99.9000) =     13.287 ms/op
     p(99.9900) =     19.694 ms/op
     p(99.9990) =     20.695 ms/op
     p(99.9999) =     20.840 ms/op
    p(100.0000) =     20.840 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.393 ± 8.878  ops/ms
ClientGrpc.existUser                       thrpt       3  10.947 ± 1.774  ops/ms
ClientGrpc.getUser                         thrpt       3  10.530 ± 2.038  ops/ms
ClientGrpc.listUser                        thrpt       3   8.040 ± 2.437  ops/ms
ClientGrpc.createUser                       avgt       3   3.005 ± 1.241   ms/op
ClientGrpc.existUser                        avgt       3   2.926 ± 1.324   ms/op
ClientGrpc.getUser                          avgt       3   2.998 ± 0.717   ms/op
ClientGrpc.listUser                         avgt       3   3.954 ± 1.204   ms/op
ClientGrpc.createUser                     sample  313068   3.065 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.345           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.047           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.711           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.891           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.276           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.962           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          19.318           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          19.890           ms/op
ClientGrpc.existUser                      sample  330668   2.901 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.495           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.896           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.498           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.674           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.100           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.430           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          14.830           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.629           ms/op
ClientGrpc.getUser                        sample  312997   3.067 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.546           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.056           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.719           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.908           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.260           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.889           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          24.976           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          25.919           ms/op
ClientGrpc.listUser                       sample  245024   3.916 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.171           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.789           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.751           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.431           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.562           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.287           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          19.694           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          20.840           ms/op
