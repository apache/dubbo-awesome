# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.409 ops/ms
# Warmup Iteration   2: 5.482 ops/ms
# Warmup Iteration   3: 9.153 ops/ms
Iteration   1: 9.970 ops/ms
Iteration   2: 10.128 ops/ms
Iteration   3: 9.941 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  10.013 ±(99.9%) 1.828 ops/ms [Average]
  (min, avg, max) = (9.941, 10.013, 10.128), stdev = 0.100
  CI (99.9%): [8.185, 11.841] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 3.448 ops/ms
# Warmup Iteration   2: 9.604 ops/ms
# Warmup Iteration   3: 9.776 ops/ms
Iteration   1: 10.655 ops/ms
Iteration   2: 10.421 ops/ms
Iteration   3: 10.557 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.544 ±(99.9%) 2.145 ops/ms [Average]
  (min, avg, max) = (10.421, 10.544, 10.655), stdev = 0.118
  CI (99.9%): [8.400, 12.689] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.709 ops/ms
# Warmup Iteration   2: 9.229 ops/ms
# Warmup Iteration   3: 9.731 ops/ms
Iteration   1: 10.194 ops/ms
Iteration   2: 10.120 ops/ms
Iteration   3: 10.007 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.107 ±(99.9%) 1.717 ops/ms [Average]
  (min, avg, max) = (10.007, 10.107, 10.194), stdev = 0.094
  CI (99.9%): [8.390, 11.824] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.144 ops/ms
# Warmup Iteration   2: 7.570 ops/ms
# Warmup Iteration   3: 8.269 ops/ms
Iteration   1: 8.394 ops/ms
Iteration   2: 8.385 ops/ms
Iteration   3: 8.482 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.421 ±(99.9%) 0.968 ops/ms [Average]
  (min, avg, max) = (8.385, 8.421, 8.482), stdev = 0.053
  CI (99.9%): [7.452, 9.389] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 9.346 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.543 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.306 ±(99.9%) 0.004 ms/op
Iteration   1: 3.276 ±(99.9%) 0.009 ms/op
Iteration   2: 3.236 ±(99.9%) 0.006 ms/op
Iteration   3: 3.205 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.239 ±(99.9%) 0.650 ms/op [Average]
  (min, avg, max) = (3.205, 3.239, 3.276), stdev = 0.036
  CI (99.9%): [2.589, 3.889] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 7.418 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.359 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.068 ±(99.9%) 0.004 ms/op
Iteration   1: 3.029 ±(99.9%) 0.007 ms/op
Iteration   2: 3.106 ±(99.9%) 0.009 ms/op
Iteration   3: 3.090 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.075 ±(99.9%) 0.741 ms/op [Average]
  (min, avg, max) = (3.029, 3.075, 3.106), stdev = 0.041
  CI (99.9%): [2.334, 3.816] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 7.373 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.555 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.294 ±(99.9%) 0.005 ms/op
Iteration   1: 3.171 ±(99.9%) 0.007 ms/op
Iteration   2: 3.213 ±(99.9%) 0.007 ms/op
Iteration   3: 3.174 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.186 ±(99.9%) 0.425 ms/op [Average]
  (min, avg, max) = (3.171, 3.186, 3.213), stdev = 0.023
  CI (99.9%): [2.761, 3.611] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 9.426 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 4.066 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.774 ±(99.9%) 0.007 ms/op
Iteration   1: 3.658 ±(99.9%) 0.010 ms/op
Iteration   2: 3.639 ±(99.9%) 0.009 ms/op
Iteration   3: 3.608 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.635 ±(99.9%) 0.460 ms/op [Average]
  (min, avg, max) = (3.608, 3.635, 3.658), stdev = 0.025
  CI (99.9%): [3.175, 4.095] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 8.184 ±(99.9%) 0.100 ms/op
# Warmup Iteration   2: 3.727 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.297 ±(99.9%) 0.009 ms/op
Iteration   1: 3.240 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.296 ms/op
                 createUser·p0.50:   3.207 ms/op
                 createUser·p0.90:   3.613 ms/op
                 createUser·p0.95:   3.969 ms/op
                 createUser·p0.99:   5.661 ms/op
                 createUser·p0.999:  11.565 ms/op
                 createUser·p0.9999: 19.239 ms/op
                 createUser·p1.00:   20.709 ms/op

Iteration   2: 3.195 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.184 ms/op
                 createUser·p0.50:   3.166 ms/op
                 createUser·p0.90:   3.416 ms/op
                 createUser·p0.95:   3.826 ms/op
                 createUser·p0.99:   6.119 ms/op
                 createUser·p0.999:  17.595 ms/op
                 createUser·p0.9999: 20.315 ms/op
                 createUser·p1.00:   23.069 ms/op

Iteration   3: 3.172 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.214 ms/op
                 createUser·p0.50:   3.101 ms/op
                 createUser·p0.90:   3.514 ms/op
                 createUser·p0.95:   3.858 ms/op
                 createUser·p0.99:   5.693 ms/op
                 createUser·p0.999:  14.451 ms/op
                 createUser·p0.9999: 19.333 ms/op
                 createUser·p1.00:   20.152 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 299737
  mean =      3.202 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22983 
    [ 2.500,  5.000) = 270465 
    [ 5.000,  7.500) = 5274 
    [ 7.500, 10.000) = 524 
    [10.000, 12.500) = 111 
    [12.500, 15.000) = 66 
    [15.000, 17.500) = 70 
    [17.500, 20.000) = 226 
    [20.000, 22.500) = 17 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.184 ms/op
     p(50.0000) =      3.162 ms/op
     p(90.0000) =      3.523 ms/op
     p(95.0000) =      3.895 ms/op
     p(99.0000) =      5.784 ms/op
     p(99.9000) =     16.761 ms/op
     p(99.9900) =     19.661 ms/op
     p(99.9990) =     21.725 ms/op
     p(99.9999) =     23.069 ms/op
    p(100.0000) =     23.069 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 6.690 ±(99.9%) 0.077 ms/op
# Warmup Iteration   2: 3.488 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.124 ±(99.9%) 0.007 ms/op
Iteration   1: 3.131 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.040 ms/op
                 existUser·p0.50:   2.994 ms/op
                 existUser·p0.90:   3.478 ms/op
                 existUser·p0.95:   3.871 ms/op
                 existUser·p0.99:   5.669 ms/op
                 existUser·p0.999:  9.322 ms/op
                 existUser·p0.9999: 20.118 ms/op
                 existUser·p1.00:   21.201 ms/op

Iteration   2: 3.260 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.969 ms/op
                 existUser·p0.50:   3.158 ms/op
                 existUser·p0.90:   3.822 ms/op
                 existUser·p0.95:   4.211 ms/op
                 existUser·p0.99:   5.489 ms/op
                 existUser·p0.999:  13.318 ms/op
                 existUser·p0.9999: 19.601 ms/op
                 existUser·p1.00:   19.923 ms/op

Iteration   3: 3.043 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   1.317 ms/op
                 existUser·p0.50:   3.068 ms/op
                 existUser·p0.90:   3.203 ms/op
                 existUser·p0.95:   3.338 ms/op
                 existUser·p0.99:   4.039 ms/op
                 existUser·p0.999:  13.681 ms/op
                 existUser·p0.9999: 22.429 ms/op
                 existUser·p1.00:   25.297 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 305480
  mean =      3.142 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17652 
    [ 2.500,  5.000) = 282680 
    [ 5.000,  7.500) = 4387 
    [ 7.500, 10.000) = 363 
    [10.000, 12.500) = 42 
    [12.500, 15.000) = 68 
    [15.000, 17.500) = 60 
    [17.500, 20.000) = 182 
    [20.000, 22.500) = 38 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.969 ms/op
     p(50.0000) =      3.072 ms/op
     p(90.0000) =      3.506 ms/op
     p(95.0000) =      3.871 ms/op
     p(99.0000) =      5.456 ms/op
     p(99.9000) =     13.664 ms/op
     p(99.9900) =     20.906 ms/op
     p(99.9990) =     22.575 ms/op
     p(99.9999) =     25.297 ms/op
    p(100.0000) =     25.297 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 7.652 ±(99.9%) 0.097 ms/op
# Warmup Iteration   2: 3.555 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.270 ±(99.9%) 0.009 ms/op
Iteration   1: 3.333 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.294 ms/op
                 getUser·p0.50:   3.199 ms/op
                 getUser·p0.90:   3.801 ms/op
                 getUser·p0.95:   4.366 ms/op
                 getUser·p0.99:   6.308 ms/op
                 getUser·p0.999:  19.042 ms/op
                 getUser·p0.9999: 21.738 ms/op
                 getUser·p1.00:   22.610 ms/op

Iteration   2: 3.206 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.231 ms/op
                 getUser·p0.50:   3.109 ms/op
                 getUser·p0.90:   3.523 ms/op
                 getUser·p0.95:   3.846 ms/op
                 getUser·p0.99:   5.513 ms/op
                 getUser·p0.999:  10.256 ms/op
                 getUser·p0.9999: 22.776 ms/op
                 getUser·p1.00:   23.364 ms/op

Iteration   3: 3.264 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.231 ms/op
                 getUser·p0.50:   3.158 ms/op
                 getUser·p0.90:   3.752 ms/op
                 getUser·p0.95:   3.998 ms/op
                 getUser·p0.99:   5.685 ms/op
                 getUser·p0.999:  12.209 ms/op
                 getUser·p0.9999: 23.567 ms/op
                 getUser·p1.00:   24.117 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 293713
  mean =      3.267 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9573 
    [ 2.500,  5.000) = 276859 
    [ 5.000,  7.500) = 6307 
    [ 7.500, 10.000) = 530 
    [10.000, 12.500) = 116 
    [12.500, 15.000) = 12 
    [15.000, 17.500) = 28 
    [17.500, 20.000) = 84 
    [20.000, 22.500) = 168 
    [22.500, 25.000) = 36 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.294 ms/op
     p(50.0000) =      3.154 ms/op
     p(90.0000) =      3.707 ms/op
     p(95.0000) =      4.076 ms/op
     p(99.0000) =      5.849 ms/op
     p(99.9000) =     16.307 ms/op
     p(99.9900) =     22.610 ms/op
     p(99.9990) =     24.087 ms/op
     p(99.9999) =     24.117 ms/op
    p(100.0000) =     24.117 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 8.476 ±(99.9%) 0.114 ms/op
# Warmup Iteration   2: 4.096 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.875 ±(99.9%) 0.012 ms/op
Iteration   1: 3.743 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.669 ms/op
                 listUser·p0.50:   3.588 ms/op
                 listUser·p0.90:   4.035 ms/op
                 listUser·p0.95:   4.276 ms/op
                 listUser·p0.99:   6.767 ms/op
                 listUser·p0.999:  18.226 ms/op
                 listUser·p0.9999: 23.868 ms/op
                 listUser·p1.00:   24.576 ms/op

Iteration   2: 3.771 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.064 ms/op
                 listUser·p0.50:   3.703 ms/op
                 listUser·p0.90:   4.055 ms/op
                 listUser·p0.95:   4.342 ms/op
                 listUser·p0.99:   6.939 ms/op
                 listUser·p0.999:  12.714 ms/op
                 listUser·p0.9999: 14.385 ms/op
                 listUser·p1.00:   14.451 ms/op

Iteration   3: 3.812 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.997 ms/op
                 listUser·p0.50:   3.678 ms/op
                 listUser·p0.90:   4.157 ms/op
                 listUser·p0.95:   4.448 ms/op
                 listUser·p0.99:   6.965 ms/op
                 listUser·p0.999:  13.701 ms/op
                 listUser·p0.9999: 14.975 ms/op
                 listUser·p1.00:   15.041 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 254179
  mean =      3.775 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 61 
    [ 2.500,  5.000) = 246708 
    [ 5.000,  7.500) = 5605 
    [ 7.500, 10.000) = 1080 
    [10.000, 12.500) = 304 
    [12.500, 15.000) = 293 
    [15.000, 17.500) = 27 
    [17.500, 20.000) = 50 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 33 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.669 ms/op
     p(50.0000) =      3.670 ms/op
     p(90.0000) =      4.092 ms/op
     p(95.0000) =      4.350 ms/op
     p(99.0000) =      6.881 ms/op
     p(99.9000) =     13.959 ms/op
     p(99.9900) =     22.891 ms/op
     p(99.9990) =     24.490 ms/op
     p(99.9999) =     24.576 ms/op
    p(100.0000) =     24.576 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  10.013 ± 1.828  ops/ms
ClientPb.existUser                       thrpt       3  10.544 ± 2.145  ops/ms
ClientPb.getUser                         thrpt       3  10.107 ± 1.717  ops/ms
ClientPb.listUser                        thrpt       3   8.421 ± 0.968  ops/ms
ClientPb.createUser                       avgt       3   3.239 ± 0.650   ms/op
ClientPb.existUser                        avgt       3   3.075 ± 0.741   ms/op
ClientPb.getUser                          avgt       3   3.186 ± 0.425   ms/op
ClientPb.listUser                         avgt       3   3.635 ± 0.460   ms/op
ClientPb.createUser                     sample  299737   3.202 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.184           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.162           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.523           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.895           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.784           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.761           ms/op
ClientPb.createUser:createUser·p0.9999  sample          19.661           ms/op
ClientPb.createUser:createUser·p1.00    sample          23.069           ms/op
ClientPb.existUser                      sample  305480   3.142 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.969           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.072           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.506           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.871           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.456           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.664           ms/op
ClientPb.existUser:existUser·p0.9999    sample          20.906           ms/op
ClientPb.existUser:existUser·p1.00      sample          25.297           ms/op
ClientPb.getUser                        sample  293713   3.267 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.294           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.154           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.707           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.076           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.849           ms/op
ClientPb.getUser:getUser·p0.999         sample          16.307           ms/op
ClientPb.getUser:getUser·p0.9999        sample          22.610           ms/op
ClientPb.getUser:getUser·p1.00          sample          24.117           ms/op
ClientPb.listUser                       sample  254179   3.775 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.669           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.670           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.092           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.350           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.881           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.959           ms/op
ClientPb.listUser:listUser·p0.9999      sample          22.891           ms/op
ClientPb.listUser:listUser·p1.00        sample          24.576           ms/op
