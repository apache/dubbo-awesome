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
# Warmup Iteration   1: 2.707 ops/ms
# Warmup Iteration   2: 5.104 ops/ms
# Warmup Iteration   3: 6.760 ops/ms
Iteration   1: 6.731 ops/ms
Iteration   2: 6.904 ops/ms
Iteration   3: 7.058 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  6.897 ±(99.9%) 2.983 ops/ms [Average]
  (min, avg, max) = (6.731, 6.897, 7.058), stdev = 0.164
  CI (99.9%): [3.914, 9.881] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:05
# Fork: 1 of 1
# Warmup Iteration   1: 5.006 ops/ms
# Warmup Iteration   2: 7.662 ops/ms
# Warmup Iteration   3: 7.824 ops/ms
Iteration   1: 8.008 ops/ms
Iteration   2: 8.024 ops/ms
Iteration   3: 8.360 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.131 ±(99.9%) 3.622 ops/ms [Average]
  (min, avg, max) = (8.008, 8.131, 8.360), stdev = 0.199
  CI (99.9%): [4.508, 11.753] (assumes normal distribution)


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
# Warmup Iteration   1: 4.227 ops/ms
# Warmup Iteration   2: 6.911 ops/ms
# Warmup Iteration   3: 7.199 ops/ms
Iteration   1: 7.304 ops/ms
Iteration   2: 7.443 ops/ms
Iteration   3: 7.628 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.458 ±(99.9%) 2.971 ops/ms [Average]
  (min, avg, max) = (7.304, 7.458, 7.628), stdev = 0.163
  CI (99.9%): [4.488, 10.429] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 3.644 ops/ms
# Warmup Iteration   2: 5.216 ops/ms
# Warmup Iteration   3: 6.153 ops/ms
Iteration   1: 5.920 ops/ms
Iteration   2: 6.076 ops/ms
Iteration   3: 6.133 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.043 ±(99.9%) 2.011 ops/ms [Average]
  (min, avg, max) = (5.920, 6.043, 6.133), stdev = 0.110
  CI (99.9%): [4.033, 8.054] (assumes normal distribution)


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
# Warmup Iteration   1: 6.701 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 4.441 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.287 ±(99.9%) 0.007 ms/op
Iteration   1: 4.284 ±(99.9%) 0.003 ms/op
Iteration   2: 4.180 ±(99.9%) 0.003 ms/op
Iteration   3: 4.326 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.263 ±(99.9%) 1.372 ms/op [Average]
  (min, avg, max) = (4.180, 4.263, 4.326), stdev = 0.075
  CI (99.9%): [2.892, 5.635] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 6.262 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 4.507 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.187 ±(99.9%) 0.004 ms/op
Iteration   1: 4.009 ±(99.9%) 0.004 ms/op
Iteration   2: 3.923 ±(99.9%) 0.003 ms/op
Iteration   3: 4.044 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.992 ±(99.9%) 1.141 ms/op [Average]
  (min, avg, max) = (3.923, 3.992, 4.044), stdev = 0.063
  CI (99.9%): [2.851, 5.133] (assumes normal distribution)


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
# Warmup Iteration   1: 5.824 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 4.601 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.420 ±(99.9%) 0.006 ms/op
Iteration   1: 4.194 ±(99.9%) 0.009 ms/op
Iteration   2: 4.147 ±(99.9%) 0.004 ms/op
Iteration   3: 4.232 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.191 ±(99.9%) 0.772 ms/op [Average]
  (min, avg, max) = (4.147, 4.191, 4.232), stdev = 0.042
  CI (99.9%): [3.419, 4.963] (assumes normal distribution)


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
# Warmup Iteration   1: 8.840 ±(99.9%) 0.060 ms/op
# Warmup Iteration   2: 6.230 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 5.717 ±(99.9%) 0.014 ms/op
Iteration   1: 5.635 ±(99.9%) 0.016 ms/op
Iteration   2: 5.597 ±(99.9%) 0.017 ms/op
Iteration   3: 5.399 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.544 ±(99.9%) 2.304 ms/op [Average]
  (min, avg, max) = (5.399, 5.544, 5.635), stdev = 0.126
  CI (99.9%): [3.239, 7.848] (assumes normal distribution)


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
# Warmup Iteration   1: 6.783 ±(99.9%) 0.077 ms/op
# Warmup Iteration   2: 4.627 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.512 ±(99.9%) 0.015 ms/op
Iteration   1: 4.476 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.298 ms/op
                 createUser·p0.50:   4.317 ms/op
                 createUser·p0.90:   5.718 ms/op
                 createUser·p0.95:   6.267 ms/op
                 createUser·p0.99:   8.004 ms/op
                 createUser·p0.999:  12.578 ms/op
                 createUser·p0.9999: 16.119 ms/op
                 createUser·p1.00:   16.515 ms/op

Iteration   2: 4.338 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.235 ms/op
                 createUser·p0.50:   4.227 ms/op
                 createUser·p0.90:   5.366 ms/op
                 createUser·p0.95:   5.898 ms/op
                 createUser·p0.99:   8.077 ms/op
                 createUser·p0.999:  17.505 ms/op
                 createUser·p0.9999: 29.618 ms/op
                 createUser·p1.00:   29.950 ms/op

Iteration   3: 4.348 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   0.918 ms/op
                 createUser·p0.50:   4.219 ms/op
                 createUser·p0.90:   5.456 ms/op
                 createUser·p0.95:   5.972 ms/op
                 createUser·p0.99:   8.069 ms/op
                 createUser·p0.999:  14.546 ms/op
                 createUser·p0.9999: 19.769 ms/op
                 createUser·p1.00:   20.283 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 218889
  mean =      4.387 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3999 
    [ 2.500,  5.000) = 171186 
    [ 5.000,  7.500) = 40667 
    [ 7.500, 10.000) = 2348 
    [10.000, 12.500) = 386 
    [12.500, 15.000) = 96 
    [15.000, 17.500) = 105 
    [17.500, 20.000) = 45 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.918 ms/op
     p(50.0000) =      4.252 ms/op
     p(90.0000) =      5.521 ms/op
     p(95.0000) =      6.070 ms/op
     p(99.0000) =      8.045 ms/op
     p(99.9000) =     14.751 ms/op
     p(99.9900) =     29.003 ms/op
     p(99.9990) =     29.899 ms/op
     p(99.9999) =     29.950 ms/op
    p(100.0000) =     29.950 ms/op


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
# Warmup Iteration   1: 5.804 ±(99.9%) 0.068 ms/op
# Warmup Iteration   2: 4.198 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.022 ±(99.9%) 0.012 ms/op
Iteration   1: 3.970 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   0.769 ms/op
                 existUser·p0.50:   3.838 ms/op
                 existUser·p0.90:   5.030 ms/op
                 existUser·p0.95:   5.595 ms/op
                 existUser·p0.99:   7.901 ms/op
                 existUser·p0.999:  14.839 ms/op
                 existUser·p0.9999: 33.061 ms/op
                 existUser·p1.00:   33.456 ms/op

Iteration   2: 3.952 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.900 ms/op
                 existUser·p0.50:   3.822 ms/op
                 existUser·p0.90:   4.866 ms/op
                 existUser·p0.95:   5.358 ms/op
                 existUser·p0.99:   7.234 ms/op
                 existUser·p0.999:  13.468 ms/op
                 existUser·p0.9999: 18.856 ms/op
                 existUser·p1.00:   19.235 ms/op

Iteration   3: 4.137 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   0.973 ms/op
                 existUser·p0.50:   3.990 ms/op
                 existUser·p0.90:   5.177 ms/op
                 existUser·p0.95:   5.702 ms/op
                 existUser·p0.99:   7.332 ms/op
                 existUser·p0.999:  14.392 ms/op
                 existUser·p0.9999: 22.839 ms/op
                 existUser·p1.00:   23.757 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 238880
  mean =      4.018 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6111 
    [ 2.500,  5.000) = 207753 
    [ 5.000,  7.500) = 22629 
    [ 7.500, 10.000) = 1579 
    [10.000, 12.500) = 443 
    [12.500, 15.000) = 183 
    [15.000, 17.500) = 47 
    [17.500, 20.000) = 44 
    [20.000, 22.500) = 42 
    [22.500, 25.000) = 17 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 11 
    [32.500, 35.000) = 21 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.769 ms/op
     p(50.0000) =      3.879 ms/op
     p(90.0000) =      5.030 ms/op
     p(95.0000) =      5.562 ms/op
     p(99.0000) =      7.496 ms/op
     p(99.9000) =     13.812 ms/op
     p(99.9900) =     32.378 ms/op
     p(99.9990) =     33.325 ms/op
     p(99.9999) =     33.456 ms/op
    p(100.0000) =     33.456 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 7.188 ±(99.9%) 0.085 ms/op
# Warmup Iteration   2: 4.723 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.439 ±(99.9%) 0.014 ms/op
Iteration   1: 4.234 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.253 ms/op
                 getUser·p0.50:   4.080 ms/op
                 getUser·p0.90:   5.341 ms/op
                 getUser·p0.95:   5.849 ms/op
                 getUser·p0.99:   7.954 ms/op
                 getUser·p0.999:  12.960 ms/op
                 getUser·p0.9999: 16.331 ms/op
                 getUser·p1.00:   16.744 ms/op

Iteration   2: 4.221 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.163 ms/op
                 getUser·p0.50:   4.104 ms/op
                 getUser·p0.90:   5.390 ms/op
                 getUser·p0.95:   5.920 ms/op
                 getUser·p0.99:   7.725 ms/op
                 getUser·p0.999:  13.345 ms/op
                 getUser·p0.9999: 27.632 ms/op
                 getUser·p1.00:   27.918 ms/op

Iteration   3: 4.183 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   0.896 ms/op
                 getUser·p0.50:   4.088 ms/op
                 getUser·p0.90:   5.251 ms/op
                 getUser·p0.95:   5.693 ms/op
                 getUser·p0.99:   6.963 ms/op
                 getUser·p0.999:  10.100 ms/op
                 getUser·p0.9999: 20.186 ms/op
                 getUser·p1.00:   20.808 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 227822
  mean =      4.212 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4707 
    [ 2.500,  5.000) = 186841 
    [ 5.000,  7.500) = 33975 
    [ 7.500, 10.000) = 1814 
    [10.000, 12.500) = 250 
    [12.500, 15.000) = 52 
    [15.000, 17.500) = 67 
    [17.500, 20.000) = 76 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 13 

  Percentiles, ms/op:
      p(0.0000) =      0.896 ms/op
     p(50.0000) =      4.088 ms/op
     p(90.0000) =      5.325 ms/op
     p(95.0000) =      5.816 ms/op
     p(99.0000) =      7.518 ms/op
     p(99.9000) =     12.742 ms/op
     p(99.9900) =     27.237 ms/op
     p(99.9990) =     27.876 ms/op
     p(99.9999) =     27.918 ms/op
    p(100.0000) =     27.918 ms/op


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
# Warmup Iteration   1: 8.056 ±(99.9%) 0.105 ms/op
# Warmup Iteration   2: 6.306 ±(99.9%) 0.031 ms/op
# Warmup Iteration   3: 5.891 ±(99.9%) 0.027 ms/op
Iteration   1: 5.602 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   1.067 ms/op
                 listUser·p0.50:   5.243 ms/op
                 listUser·p0.90:   7.430 ms/op
                 listUser·p0.95:   8.520 ms/op
                 listUser·p0.99:   11.502 ms/op
                 listUser·p0.999:  19.394 ms/op
                 listUser·p0.9999: 24.489 ms/op
                 listUser·p1.00:   25.559 ms/op

Iteration   2: 5.705 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   1.583 ms/op
                 listUser·p0.50:   5.325 ms/op
                 listUser·p0.90:   7.799 ms/op
                 listUser·p0.95:   8.864 ms/op
                 listUser·p0.99:   11.522 ms/op
                 listUser·p0.999:  20.248 ms/op
                 listUser·p0.9999: 32.997 ms/op
                 listUser·p1.00:   33.489 ms/op

Iteration   3: 5.427 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   1.212 ms/op
                 listUser·p0.50:   5.120 ms/op
                 listUser·p0.90:   7.397 ms/op
                 listUser·p0.95:   8.307 ms/op
                 listUser·p0.99:   10.322 ms/op
                 listUser·p0.999:  21.764 ms/op
                 listUser·p0.9999: 33.409 ms/op
                 listUser·p1.00:   34.210 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 172049
  mean =      5.576 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 222 
    [ 2.500,  5.000) = 70285 
    [ 5.000,  7.500) = 83843 
    [ 7.500, 10.000) = 14443 
    [10.000, 12.500) = 2350 
    [12.500, 15.000) = 483 
    [15.000, 17.500) = 128 
    [17.500, 20.000) = 111 
    [20.000, 22.500) = 85 
    [22.500, 25.000) = 41 
    [25.000, 27.500) = 2 
    [27.500, 30.000) = 4 
    [30.000, 32.500) = 35 
    [32.500, 35.000) = 17 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.067 ms/op
     p(50.0000) =      5.226 ms/op
     p(90.0000) =      7.545 ms/op
     p(95.0000) =      8.552 ms/op
     p(99.0000) =     11.174 ms/op
     p(99.9000) =     20.475 ms/op
     p(99.9900) =     32.577 ms/op
     p(99.9990) =     34.115 ms/op
     p(99.9999) =     34.210 ms/op
    p(100.0000) =     34.210 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   6.897 ± 2.983  ops/ms
ClientGrpc.existUser                       thrpt       3   8.131 ± 3.622  ops/ms
ClientGrpc.getUser                         thrpt       3   7.458 ± 2.971  ops/ms
ClientGrpc.listUser                        thrpt       3   6.043 ± 2.011  ops/ms
ClientGrpc.createUser                       avgt       3   4.263 ± 1.372   ms/op
ClientGrpc.existUser                        avgt       3   3.992 ± 1.141   ms/op
ClientGrpc.getUser                          avgt       3   4.191 ± 0.772   ms/op
ClientGrpc.listUser                         avgt       3   5.544 ± 2.304   ms/op
ClientGrpc.createUser                     sample  218889   4.387 ± 0.008   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.918           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.252           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.521           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           6.070           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           8.045           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          14.751           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          29.003           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          29.950           ms/op
ClientGrpc.existUser                      sample  238880   4.018 ± 0.007   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.769           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.879           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.030           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.562           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           7.496           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          13.812           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          32.378           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          33.456           ms/op
ClientGrpc.getUser                        sample  227822   4.212 ± 0.007   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.896           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.088           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.325           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.816           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.518           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          12.742           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          27.237           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          27.918           ms/op
ClientGrpc.listUser                       sample  172049   5.576 ± 0.013   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.067           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.226           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.545           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           8.552           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          11.174           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          20.475           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          32.577           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          34.210           ms/op
