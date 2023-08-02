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
# Warmup Iteration   1: 3.864 ops/ms
# Warmup Iteration   2: 8.747 ops/ms
# Warmup Iteration   3: 10.371 ops/ms
Iteration   1: 10.532 ops/ms
Iteration   2: 10.501 ops/ms
Iteration   3: 10.627 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.553 ±(99.9%) 1.203 ops/ms [Average]
  (min, avg, max) = (10.501, 10.553, 10.627), stdev = 0.066
  CI (99.9%): [9.351, 11.756] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 7.744 ops/ms
# Warmup Iteration   2: 10.687 ops/ms
# Warmup Iteration   3: 11.099 ops/ms
Iteration   1: 11.114 ops/ms
Iteration   2: 11.100 ops/ms
Iteration   3: 11.298 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.171 ±(99.9%) 2.013 ops/ms [Average]
  (min, avg, max) = (11.100, 11.171, 11.298), stdev = 0.110
  CI (99.9%): [9.158, 13.184] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.071 ops/ms
# Warmup Iteration   2: 10.183 ops/ms
# Warmup Iteration   3: 10.539 ops/ms
Iteration   1: 10.684 ops/ms
Iteration   2: 10.500 ops/ms
Iteration   3: 10.529 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.571 ±(99.9%) 1.808 ops/ms [Average]
  (min, avg, max) = (10.500, 10.571, 10.684), stdev = 0.099
  CI (99.9%): [8.763, 12.379] (assumes normal distribution)


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
# Warmup Iteration   1: 5.035 ops/ms
# Warmup Iteration   2: 7.596 ops/ms
# Warmup Iteration   3: 7.804 ops/ms
Iteration   1: 8.129 ops/ms
Iteration   2: 7.959 ops/ms
Iteration   3: 7.913 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.000 ±(99.9%) 2.077 ops/ms [Average]
  (min, avg, max) = (7.913, 8.000, 8.129), stdev = 0.114
  CI (99.9%): [5.923, 10.078] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.256 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.104 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.043 ±(99.9%) 0.003 ms/op
Iteration   1: 3.028 ±(99.9%) 0.003 ms/op
Iteration   2: 2.940 ±(99.9%) 0.005 ms/op
Iteration   3: 3.051 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.006 ±(99.9%) 1.067 ms/op [Average]
  (min, avg, max) = (2.940, 3.006, 3.051), stdev = 0.058
  CI (99.9%): [1.939, 4.074] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 4.057 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.999 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.872 ±(99.9%) 0.002 ms/op
Iteration   1: 2.883 ±(99.9%) 0.003 ms/op
Iteration   2: 2.846 ±(99.9%) 0.003 ms/op
Iteration   3: 2.902 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.877 ±(99.9%) 0.519 ms/op [Average]
  (min, avg, max) = (2.846, 2.877, 2.902), stdev = 0.028
  CI (99.9%): [2.359, 3.396] (assumes normal distribution)


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
# Warmup Iteration   1: 4.195 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.060 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.062 ±(99.9%) 0.003 ms/op
Iteration   1: 3.057 ±(99.9%) 0.003 ms/op
Iteration   2: 3.045 ±(99.9%) 0.003 ms/op
Iteration   3: 3.011 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.038 ±(99.9%) 0.433 ms/op [Average]
  (min, avg, max) = (3.011, 3.038, 3.057), stdev = 0.024
  CI (99.9%): [2.605, 3.471] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 5.340 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 4.026 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.983 ±(99.9%) 0.038 ms/op
Iteration   1: 3.992 ±(99.9%) 0.019 ms/op
Iteration   2: 4.026 ±(99.9%) 0.006 ms/op
Iteration   3: 3.939 ±(99.9%) 0.023 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.985 ±(99.9%) 0.803 ms/op [Average]
  (min, avg, max) = (3.939, 3.985, 4.026), stdev = 0.044
  CI (99.9%): [3.182, 4.789] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.245 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.198 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.052 ±(99.9%) 0.007 ms/op
Iteration   1: 2.980 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.815 ms/op
                 createUser·p0.50:   2.961 ms/op
                 createUser·p0.90:   3.449 ms/op
                 createUser·p0.95:   3.666 ms/op
                 createUser·p0.99:   4.727 ms/op
                 createUser·p0.999:  7.974 ms/op
                 createUser·p0.9999: 13.194 ms/op
                 createUser·p1.00:   13.402 ms/op

Iteration   2: 3.056 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.553 ms/op
                 createUser·p0.50:   3.019 ms/op
                 createUser·p0.90:   3.670 ms/op
                 createUser·p0.95:   3.846 ms/op
                 createUser·p0.99:   4.776 ms/op
                 createUser·p0.999:  8.315 ms/op
                 createUser·p0.9999: 17.089 ms/op
                 createUser·p1.00:   18.678 ms/op

Iteration   3: 3.007 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.748 ms/op
                 createUser·p0.50:   2.994 ms/op
                 createUser·p0.90:   3.617 ms/op
                 createUser·p0.95:   3.830 ms/op
                 createUser·p0.99:   4.719 ms/op
                 createUser·p0.999:  12.489 ms/op
                 createUser·p0.9999: 17.871 ms/op
                 createUser·p1.00:   19.661 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 318485
  mean =      3.014 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1377 
    [ 1.250,  2.500) = 31308 
    [ 2.500,  3.750) = 266681 
    [ 3.750,  5.000) = 16840 
    [ 5.000,  6.250) = 1192 
    [ 6.250,  7.500) = 512 
    [ 7.500,  8.750) = 233 
    [ 8.750, 10.000) = 31 
    [10.000, 11.250) = 23 
    [11.250, 12.500) = 46 
    [12.500, 13.750) = 88 
    [13.750, 15.000) = 37 
    [15.000, 16.250) = 19 
    [16.250, 17.500) = 65 
    [17.500, 18.750) = 27 

  Percentiles, ms/op:
      p(0.0000) =      0.553 ms/op
     p(50.0000) =      2.990 ms/op
     p(90.0000) =      3.588 ms/op
     p(95.0000) =      3.805 ms/op
     p(99.0000) =      4.735 ms/op
     p(99.9000) =      9.790 ms/op
     p(99.9900) =     17.564 ms/op
     p(99.9990) =     19.255 ms/op
     p(99.9999) =     19.661 ms/op
    p(100.0000) =     19.661 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.846 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.061 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.908 ±(99.9%) 0.006 ms/op
Iteration   1: 2.907 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.571 ms/op
                 existUser·p0.50:   2.884 ms/op
                 existUser·p0.90:   3.322 ms/op
                 existUser·p0.95:   3.547 ms/op
                 existUser·p0.99:   4.424 ms/op
                 existUser·p0.999:  7.266 ms/op
                 existUser·p0.9999: 12.993 ms/op
                 existUser·p1.00:   13.369 ms/op

Iteration   2: 2.872 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.780 ms/op
                 existUser·p0.50:   2.867 ms/op
                 existUser·p0.90:   3.375 ms/op
                 existUser·p0.95:   3.641 ms/op
                 existUser·p0.99:   4.276 ms/op
                 existUser·p0.999:  6.775 ms/op
                 existUser·p0.9999: 18.346 ms/op
                 existUser·p1.00:   20.120 ms/op

Iteration   3: 2.868 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.708 ms/op
                 existUser·p0.50:   2.855 ms/op
                 existUser·p0.90:   3.269 ms/op
                 existUser·p0.95:   3.473 ms/op
                 existUser·p0.99:   4.473 ms/op
                 existUser·p0.999:  8.438 ms/op
                 existUser·p0.9999: 15.586 ms/op
                 existUser·p1.00:   16.482 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 332783
  mean =      2.882 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 41108 
    [ 2.500,  5.000) = 290315 
    [ 5.000,  7.500) = 1032 
    [ 7.500, 10.000) = 131 
    [10.000, 12.500) = 62 
    [12.500, 15.000) = 78 
    [15.000, 17.500) = 25 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.571 ms/op
     p(50.0000) =      2.867 ms/op
     p(90.0000) =      3.318 ms/op
     p(95.0000) =      3.559 ms/op
     p(99.0000) =      4.407 ms/op
     p(99.9000) =      7.465 ms/op
     p(99.9900) =     16.437 ms/op
     p(99.9990) =     19.694 ms/op
     p(99.9999) =     20.120 ms/op
    p(100.0000) =     20.120 ms/op


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
# Warmup Iteration   1: 4.310 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.139 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.072 ±(99.9%) 0.006 ms/op
Iteration   1: 2.997 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.859 ms/op
                 getUser·p0.50:   2.970 ms/op
                 getUser·p0.90:   3.559 ms/op
                 getUser·p0.95:   3.871 ms/op
                 getUser·p0.99:   4.841 ms/op
                 getUser·p0.999:  7.954 ms/op
                 getUser·p0.9999: 15.434 ms/op
                 getUser·p1.00:   15.679 ms/op

Iteration   2: 3.029 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.756 ms/op
                 getUser·p0.50:   2.982 ms/op
                 getUser·p0.90:   3.502 ms/op
                 getUser·p0.95:   3.826 ms/op
                 getUser·p0.99:   4.835 ms/op
                 getUser·p0.999:  11.712 ms/op
                 getUser·p0.9999: 15.898 ms/op
                 getUser·p1.00:   16.286 ms/op

Iteration   3: 3.068 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.709 ms/op
                 getUser·p0.50:   3.011 ms/op
                 getUser·p0.90:   3.621 ms/op
                 getUser·p0.95:   3.850 ms/op
                 getUser·p0.99:   4.645 ms/op
                 getUser·p0.999:  8.368 ms/op
                 getUser·p0.9999: 31.738 ms/op
                 getUser·p1.00:   32.047 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 316514
  mean =      3.031 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 25709 
    [ 2.500,  5.000) = 288459 
    [ 5.000,  7.500) = 1856 
    [ 7.500, 10.000) = 208 
    [10.000, 12.500) = 72 
    [12.500, 15.000) = 83 
    [15.000, 17.500) = 63 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 6 
    [25.000, 27.500) = 26 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 32 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.709 ms/op
     p(50.0000) =      2.986 ms/op
     p(90.0000) =      3.568 ms/op
     p(95.0000) =      3.850 ms/op
     p(99.0000) =      4.784 ms/op
     p(99.9000) =      8.536 ms/op
     p(99.9900) =     31.000 ms/op
     p(99.9990) =     31.976 ms/op
     p(99.9999) =     32.047 ms/op
    p(100.0000) =     32.047 ms/op


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
# Warmup Iteration   1: 5.629 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 4.124 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.007 ±(99.9%) 0.012 ms/op
Iteration   1: 3.971 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.386 ms/op
                 listUser·p0.50:   3.834 ms/op
                 listUser·p0.90:   4.760 ms/op
                 listUser·p0.95:   5.603 ms/op
                 listUser·p0.99:   6.963 ms/op
                 listUser·p0.999:  13.230 ms/op
                 listUser·p0.9999: 17.724 ms/op
                 listUser·p1.00:   18.416 ms/op

Iteration   2: 3.894 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.546 ms/op
                 listUser·p0.50:   3.744 ms/op
                 listUser·p0.90:   4.923 ms/op
                 listUser·p0.95:   5.652 ms/op
                 listUser·p0.99:   7.242 ms/op
                 listUser·p0.999:  15.958 ms/op
                 listUser·p0.9999: 18.146 ms/op
                 listUser·p1.00:   18.547 ms/op

Iteration   3: 3.992 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.897 ms/op
                 listUser·p0.50:   3.863 ms/op
                 listUser·p0.90:   4.686 ms/op
                 listUser·p0.95:   5.661 ms/op
                 listUser·p0.99:   6.971 ms/op
                 listUser·p0.999:  17.327 ms/op
                 listUser·p0.9999: 21.462 ms/op
                 listUser·p1.00:   21.758 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 242844
  mean =      3.952 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3367 
    [ 2.500,  5.000) = 219041 
    [ 5.000,  7.500) = 18811 
    [ 7.500, 10.000) = 1046 
    [10.000, 12.500) = 198 
    [12.500, 15.000) = 114 
    [15.000, 17.500) = 145 
    [17.500, 20.000) = 74 
    [20.000, 22.500) = 48 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.546 ms/op
     p(50.0000) =      3.817 ms/op
     p(90.0000) =      4.809 ms/op
     p(95.0000) =      5.644 ms/op
     p(99.0000) =      7.045 ms/op
     p(99.9000) =     15.616 ms/op
     p(99.9900) =     20.831 ms/op
     p(99.9990) =     21.603 ms/op
     p(99.9999) =     21.758 ms/op
    p(100.0000) =     21.758 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.553 ± 1.203  ops/ms
ClientGrpc.existUser                       thrpt       3  11.171 ± 2.013  ops/ms
ClientGrpc.getUser                         thrpt       3  10.571 ± 1.808  ops/ms
ClientGrpc.listUser                        thrpt       3   8.000 ± 2.077  ops/ms
ClientGrpc.createUser                       avgt       3   3.006 ± 1.067   ms/op
ClientGrpc.existUser                        avgt       3   2.877 ± 0.519   ms/op
ClientGrpc.getUser                          avgt       3   3.038 ± 0.433   ms/op
ClientGrpc.listUser                         avgt       3   3.985 ± 0.803   ms/op
ClientGrpc.createUser                     sample  318485   3.014 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.553           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.990           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.588           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.805           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.735           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.790           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          17.564           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          19.661           ms/op
ClientGrpc.existUser                      sample  332783   2.882 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.571           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.867           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.318           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.559           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.407           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.465           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.437           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          20.120           ms/op
ClientGrpc.getUser                        sample  316514   3.031 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.709           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.986           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.568           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.850           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.784           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.536           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          31.000           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          32.047           ms/op
ClientGrpc.listUser                       sample  242844   3.952 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.546           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.817           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.809           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.644           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.045           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.616           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          20.831           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          21.758           ms/op
