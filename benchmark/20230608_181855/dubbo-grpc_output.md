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
# Warmup Iteration   1: 2.264 ops/ms
# Warmup Iteration   2: 5.459 ops/ms
# Warmup Iteration   3: 7.343 ops/ms
Iteration   1: 7.795 ops/ms
Iteration   2: 7.853 ops/ms
Iteration   3: 7.618 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.755 ±(99.9%) 2.235 ops/ms [Average]
  (min, avg, max) = (7.618, 7.755, 7.853), stdev = 0.122
  CI (99.9%): [5.520, 9.990] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 4.794 ops/ms
# Warmup Iteration   2: 7.363 ops/ms
# Warmup Iteration   3: 8.036 ops/ms
Iteration   1: 8.116 ops/ms
Iteration   2: 8.025 ops/ms
Iteration   3: 8.217 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.119 ±(99.9%) 1.754 ops/ms [Average]
  (min, avg, max) = (8.025, 8.119, 8.217), stdev = 0.096
  CI (99.9%): [6.365, 9.873] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:59
# Fork: 1 of 1
# Warmup Iteration   1: 4.416 ops/ms
# Warmup Iteration   2: 7.256 ops/ms
# Warmup Iteration   3: 7.591 ops/ms
Iteration   1: 7.806 ops/ms
Iteration   2: 7.582 ops/ms
Iteration   3: 8.004 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.797 ±(99.9%) 3.855 ops/ms [Average]
  (min, avg, max) = (7.582, 7.797, 8.004), stdev = 0.211
  CI (99.9%): [3.942, 11.652] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 4.199 ops/ms
# Warmup Iteration   2: 5.182 ops/ms
# Warmup Iteration   3: 5.749 ops/ms
Iteration   1: 5.730 ops/ms
Iteration   2: 5.918 ops/ms
Iteration   3: 5.772 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.807 ±(99.9%) 1.795 ops/ms [Average]
  (min, avg, max) = (5.730, 5.807, 5.918), stdev = 0.098
  CI (99.9%): [4.011, 7.602] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 6.321 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 4.611 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.309 ±(99.9%) 0.005 ms/op
Iteration   1: 4.055 ±(99.9%) 0.002 ms/op
Iteration   2: 4.132 ±(99.9%) 0.004 ms/op
Iteration   3: 4.122 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.103 ±(99.9%) 0.759 ms/op [Average]
  (min, avg, max) = (4.055, 4.103, 4.132), stdev = 0.042
  CI (99.9%): [3.344, 4.862] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 6.871 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 4.679 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.073 ±(99.9%) 0.003 ms/op
Iteration   1: 3.946 ±(99.9%) 0.004 ms/op
Iteration   2: 3.937 ±(99.9%) 0.003 ms/op
Iteration   3: 3.892 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.925 ±(99.9%) 0.523 ms/op [Average]
  (min, avg, max) = (3.892, 3.925, 3.946), stdev = 0.029
  CI (99.9%): [3.402, 4.448] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 6.412 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 4.609 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.275 ±(99.9%) 0.003 ms/op
Iteration   1: 4.223 ±(99.9%) 0.002 ms/op
Iteration   2: 4.189 ±(99.9%) 0.003 ms/op
Iteration   3: 4.213 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.208 ±(99.9%) 0.313 ms/op [Average]
  (min, avg, max) = (4.189, 4.208, 4.223), stdev = 0.017
  CI (99.9%): [3.895, 4.521] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 7.340 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 6.078 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 5.553 ±(99.9%) 0.017 ms/op
Iteration   1: 5.406 ±(99.9%) 0.014 ms/op
Iteration   2: 5.176 ±(99.9%) 0.023 ms/op
Iteration   3: 5.045 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.209 ±(99.9%) 3.329 ms/op [Average]
  (min, avg, max) = (5.045, 5.209, 5.406), stdev = 0.182
  CI (99.9%): [1.880, 8.538] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 6.480 ±(99.9%) 0.076 ms/op
# Warmup Iteration   2: 4.301 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.142 ±(99.9%) 0.012 ms/op
Iteration   1: 4.016 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   0.496 ms/op
                 createUser·p0.50:   3.867 ms/op
                 createUser·p0.90:   5.087 ms/op
                 createUser·p0.95:   5.685 ms/op
                 createUser·p0.99:   7.751 ms/op
                 createUser·p0.999:  15.668 ms/op
                 createUser·p0.9999: 18.088 ms/op
                 createUser·p1.00:   18.416 ms/op

Iteration   2: 4.088 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   0.891 ms/op
                 createUser·p0.50:   3.990 ms/op
                 createUser·p0.90:   5.194 ms/op
                 createUser·p0.95:   5.677 ms/op
                 createUser·p0.99:   7.815 ms/op
                 createUser·p0.999:  12.805 ms/op
                 createUser·p0.9999: 19.848 ms/op
                 createUser·p1.00:   22.741 ms/op

Iteration   3: 4.008 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.018 ms/op
                 createUser·p0.50:   3.875 ms/op
                 createUser·p0.90:   4.991 ms/op
                 createUser·p0.95:   5.521 ms/op
                 createUser·p0.99:   7.750 ms/op
                 createUser·p0.999:  14.700 ms/op
                 createUser·p0.9999: 23.301 ms/op
                 createUser·p1.00:   24.084 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 237689
  mean =      4.037 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7162 
    [ 2.500,  5.000) = 203344 
    [ 5.000,  7.500) = 24452 
    [ 7.500, 10.000) = 2124 
    [10.000, 12.500) = 252 
    [12.500, 15.000) = 159 
    [15.000, 17.500) = 60 
    [17.500, 20.000) = 80 
    [20.000, 22.500) = 45 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.496 ms/op
     p(50.0000) =      3.908 ms/op
     p(90.0000) =      5.095 ms/op
     p(95.0000) =      5.628 ms/op
     p(99.0000) =      7.782 ms/op
     p(99.9000) =     14.565 ms/op
     p(99.9900) =     21.823 ms/op
     p(99.9990) =     23.953 ms/op
     p(99.9999) =     24.084 ms/op
    p(100.0000) =     24.084 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.763 ±(99.9%) 0.066 ms/op
# Warmup Iteration   2: 4.099 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.923 ±(99.9%) 0.011 ms/op
Iteration   1: 3.896 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.826 ms/op
                 existUser·p0.50:   3.801 ms/op
                 existUser·p0.90:   4.882 ms/op
                 existUser·p0.95:   5.415 ms/op
                 existUser·p0.99:   7.455 ms/op
                 existUser·p0.999:  12.088 ms/op
                 existUser·p0.9999: 15.106 ms/op
                 existUser·p1.00:   16.171 ms/op

Iteration   2: 3.796 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.139 ms/op
                 existUser·p0.50:   3.719 ms/op
                 existUser·p0.90:   4.588 ms/op
                 existUser·p0.95:   5.087 ms/op
                 existUser·p0.99:   7.070 ms/op
                 existUser·p0.999:  12.919 ms/op
                 existUser·p0.9999: 20.944 ms/op
                 existUser·p1.00:   21.266 ms/op

Iteration   3: 3.946 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.956 ms/op
                 existUser·p0.50:   3.822 ms/op
                 existUser·p0.90:   4.866 ms/op
                 existUser·p0.95:   5.366 ms/op
                 existUser·p0.99:   7.422 ms/op
                 existUser·p0.999:  14.139 ms/op
                 existUser·p0.9999: 23.590 ms/op
                 existUser·p1.00:   26.214 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 247476
  mean =      3.878 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11032 
    [ 2.500,  5.000) = 218187 
    [ 5.000,  7.500) = 16079 
    [ 7.500, 10.000) = 1615 
    [10.000, 12.500) = 269 
    [12.500, 15.000) = 152 
    [15.000, 17.500) = 35 
    [17.500, 20.000) = 13 
    [20.000, 22.500) = 55 
    [22.500, 25.000) = 38 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.826 ms/op
     p(50.0000) =      3.777 ms/op
     p(90.0000) =      4.784 ms/op
     p(95.0000) =      5.308 ms/op
     p(99.0000) =      7.299 ms/op
     p(99.9000) =     13.206 ms/op
     p(99.9900) =     23.036 ms/op
     p(99.9990) =     24.234 ms/op
     p(99.9999) =     26.214 ms/op
    p(100.0000) =     26.214 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 6.338 ±(99.9%) 0.084 ms/op
# Warmup Iteration   2: 4.316 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.106 ±(99.9%) 0.013 ms/op
Iteration   1: 4.024 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.039 ms/op
                 getUser·p0.50:   3.895 ms/op
                 getUser·p0.90:   5.030 ms/op
                 getUser·p0.95:   5.677 ms/op
                 getUser·p0.99:   7.900 ms/op
                 getUser·p0.999:  10.430 ms/op
                 getUser·p0.9999: 15.125 ms/op
                 getUser·p1.00:   16.040 ms/op

Iteration   2: 4.068 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   0.979 ms/op
                 getUser·p0.50:   3.899 ms/op
                 getUser·p0.90:   5.177 ms/op
                 getUser·p0.95:   5.833 ms/op
                 getUser·p0.99:   8.184 ms/op
                 getUser·p0.999:  16.101 ms/op
                 getUser·p0.9999: 20.189 ms/op
                 getUser·p1.00:   20.775 ms/op

Iteration   3: 4.115 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   0.768 ms/op
                 getUser·p0.50:   3.961 ms/op
                 getUser·p0.90:   5.251 ms/op
                 getUser·p0.95:   5.784 ms/op
                 getUser·p0.99:   8.049 ms/op
                 getUser·p0.999:  12.739 ms/op
                 getUser·p0.9999: 19.570 ms/op
                 getUser·p1.00:   20.906 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 235957
  mean =      4.069 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7526 
    [ 2.500,  5.000) = 199921 
    [ 5.000,  7.500) = 25315 
    [ 7.500, 10.000) = 2560 
    [10.000, 12.500) = 379 
    [12.500, 15.000) = 105 
    [15.000, 17.500) = 55 
    [17.500, 20.000) = 83 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.768 ms/op
     p(50.0000) =      3.916 ms/op
     p(90.0000) =      5.161 ms/op
     p(95.0000) =      5.767 ms/op
     p(99.0000) =      8.061 ms/op
     p(99.9000) =     12.845 ms/op
     p(99.9900) =     19.772 ms/op
     p(99.9990) =     20.763 ms/op
     p(99.9999) =     20.906 ms/op
    p(100.0000) =     20.906 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 7.223 ±(99.9%) 0.089 ms/op
# Warmup Iteration   2: 5.739 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 5.597 ±(99.9%) 0.021 ms/op
Iteration   1: 5.570 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   1.384 ms/op
                 listUser·p0.50:   5.243 ms/op
                 listUser·p0.90:   7.414 ms/op
                 listUser·p0.95:   8.389 ms/op
                 listUser·p0.99:   10.830 ms/op
                 listUser·p0.999:  21.579 ms/op
                 listUser·p0.9999: 24.945 ms/op
                 listUser·p1.00:   25.100 ms/op

Iteration   2: 5.695 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   0.492 ms/op
                 listUser·p0.50:   5.317 ms/op
                 listUser·p0.90:   7.774 ms/op
                 listUser·p0.95:   8.831 ms/op
                 listUser·p0.99:   11.452 ms/op
                 listUser·p0.999:  17.648 ms/op
                 listUser·p0.9999: 21.942 ms/op
                 listUser·p1.00:   23.626 ms/op

Iteration   3: 5.771 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   1.526 ms/op
                 listUser·p0.50:   5.325 ms/op
                 listUser·p0.90:   7.807 ms/op
                 listUser·p0.95:   8.913 ms/op
                 listUser·p0.99:   12.616 ms/op
                 listUser·p0.999:  24.841 ms/op
                 listUser·p0.9999: 37.087 ms/op
                 listUser·p1.00:   37.421 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 169042
  mean =      5.677 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 183 
    [ 2.500,  5.000) = 62847 
    [ 5.000,  7.500) = 87260 
    [ 7.500, 10.000) = 14847 
    [10.000, 12.500) = 2783 
    [12.500, 15.000) = 539 
    [15.000, 17.500) = 298 
    [17.500, 20.000) = 95 
    [20.000, 22.500) = 44 
    [22.500, 25.000) = 88 
    [25.000, 27.500) = 16 
    [27.500, 30.000) = 10 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 9 
    [35.000, 37.500) = 23 

  Percentiles, ms/op:
      p(0.0000) =      0.492 ms/op
     p(50.0000) =      5.292 ms/op
     p(90.0000) =      7.660 ms/op
     p(95.0000) =      8.716 ms/op
     p(99.0000) =     11.567 ms/op
     p(99.9000) =     21.752 ms/op
     p(99.9900) =     35.396 ms/op
     p(99.9990) =     37.376 ms/op
     p(99.9999) =     37.421 ms/op
    p(100.0000) =     37.421 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.755 ± 2.235  ops/ms
ClientGrpc.existUser                       thrpt       3   8.119 ± 1.754  ops/ms
ClientGrpc.getUser                         thrpt       3   7.797 ± 3.855  ops/ms
ClientGrpc.listUser                        thrpt       3   5.807 ± 1.795  ops/ms
ClientGrpc.createUser                       avgt       3   4.103 ± 0.759   ms/op
ClientGrpc.existUser                        avgt       3   3.925 ± 0.523   ms/op
ClientGrpc.getUser                          avgt       3   4.208 ± 0.313   ms/op
ClientGrpc.listUser                         avgt       3   5.209 ± 3.329   ms/op
ClientGrpc.createUser                     sample  237689   4.037 ± 0.007   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.496           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.908           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.095           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.628           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.782           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          14.565           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.823           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          24.084           ms/op
ClientGrpc.existUser                      sample  247476   3.878 ± 0.007   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.826           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.777           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.784           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.308           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           7.299           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          13.206           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          23.036           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          26.214           ms/op
ClientGrpc.getUser                        sample  235957   4.069 ± 0.007   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.768           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.916           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.161           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.767           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           8.061           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          12.845           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.772           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.906           ms/op
ClientGrpc.listUser                       sample  169042   5.677 ± 0.014   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.492           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.292           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.660           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           8.716           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          11.567           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          21.752           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          35.396           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          37.421           ms/op
