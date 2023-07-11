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
# Warmup Iteration   1: 2.304 ops/ms
# Warmup Iteration   2: 5.201 ops/ms
# Warmup Iteration   3: 8.934 ops/ms
Iteration   1: 9.722 ops/ms
Iteration   2: 9.775 ops/ms
Iteration   3: 9.835 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.777 ±(99.9%) 1.032 ops/ms [Average]
  (min, avg, max) = (9.722, 9.777, 9.835), stdev = 0.057
  CI (99.9%): [8.745, 10.809] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 3.296 ops/ms
# Warmup Iteration   2: 8.940 ops/ms
# Warmup Iteration   3: 9.799 ops/ms
Iteration   1: 10.254 ops/ms
Iteration   2: 9.928 ops/ms
Iteration   3: 10.380 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.188 ±(99.9%) 4.258 ops/ms [Average]
  (min, avg, max) = (9.928, 10.188, 10.380), stdev = 0.233
  CI (99.9%): [5.930, 14.445] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 3.006 ops/ms
# Warmup Iteration   2: 8.271 ops/ms
# Warmup Iteration   3: 9.263 ops/ms
Iteration   1: 9.385 ops/ms
Iteration   2: 9.673 ops/ms
Iteration   3: 9.620 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.559 ±(99.9%) 2.796 ops/ms [Average]
  (min, avg, max) = (9.385, 9.559, 9.673), stdev = 0.153
  CI (99.9%): [6.763, 12.356] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 3.201 ops/ms
# Warmup Iteration   2: 6.902 ops/ms
# Warmup Iteration   3: 8.191 ops/ms
Iteration   1: 8.423 ops/ms
Iteration   2: 8.149 ops/ms
Iteration   3: 8.333 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.302 ±(99.9%) 2.544 ops/ms [Average]
  (min, avg, max) = (8.149, 8.302, 8.423), stdev = 0.139
  CI (99.9%): [5.758, 10.846] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:43
# Fork: 1 of 1
# Warmup Iteration   1: 8.457 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.630 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.457 ±(99.9%) 0.002 ms/op
Iteration   1: 3.250 ±(99.9%) 0.006 ms/op
Iteration   2: 3.234 ±(99.9%) 0.009 ms/op
Iteration   3: 3.409 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.298 ±(99.9%) 1.763 ms/op [Average]
  (min, avg, max) = (3.234, 3.298, 3.409), stdev = 0.097
  CI (99.9%): [1.534, 5.061] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 7.398 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.356 ±(99.9%) 0.001 ms/op
# Warmup Iteration   3: 3.284 ±(99.9%) 0.006 ms/op
Iteration   1: 3.256 ±(99.9%) 0.004 ms/op
Iteration   2: 3.129 ±(99.9%) 0.006 ms/op
Iteration   3: 3.066 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.150 ±(99.9%) 1.769 ms/op [Average]
  (min, avg, max) = (3.066, 3.150, 3.256), stdev = 0.097
  CI (99.9%): [1.381, 4.919] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 7.632 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.550 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.347 ±(99.9%) 0.002 ms/op
Iteration   1: 3.228 ±(99.9%) 0.003 ms/op
Iteration   2: 3.204 ±(99.9%) 0.007 ms/op
Iteration   3: 3.249 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.227 ±(99.9%) 0.407 ms/op [Average]
  (min, avg, max) = (3.204, 3.227, 3.249), stdev = 0.022
  CI (99.9%): [2.820, 3.634] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 10.809 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 4.309 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.866 ±(99.9%) 0.006 ms/op
Iteration   1: 3.737 ±(99.9%) 0.010 ms/op
Iteration   2: 3.853 ±(99.9%) 0.004 ms/op
Iteration   3: 3.751 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.780 ±(99.9%) 1.156 ms/op [Average]
  (min, avg, max) = (3.737, 3.780, 3.853), stdev = 0.063
  CI (99.9%): [2.624, 4.937] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 8.745 ±(99.9%) 0.103 ms/op
# Warmup Iteration   2: 4.048 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.250 ±(99.9%) 0.009 ms/op
Iteration   1: 3.174 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.331 ms/op
                 createUser·p0.50:   3.162 ms/op
                 createUser·p0.90:   3.342 ms/op
                 createUser·p0.95:   3.494 ms/op
                 createUser·p0.99:   5.603 ms/op
                 createUser·p0.999:  12.550 ms/op
                 createUser·p0.9999: 20.313 ms/op
                 createUser·p1.00:   20.546 ms/op

Iteration   2: 3.243 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.672 ms/op
                 createUser·p0.50:   3.219 ms/op
                 createUser·p0.90:   3.625 ms/op
                 createUser·p0.95:   3.920 ms/op
                 createUser·p0.99:   5.079 ms/op
                 createUser·p0.999:  9.476 ms/op
                 createUser·p0.9999: 23.143 ms/op
                 createUser·p1.00:   25.002 ms/op

Iteration   3: 3.218 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.061 ms/op
                 createUser·p0.50:   3.158 ms/op
                 createUser·p0.90:   3.523 ms/op
                 createUser·p0.95:   3.752 ms/op
                 createUser·p0.99:   5.497 ms/op
                 createUser·p0.999:  16.576 ms/op
                 createUser·p0.9999: 21.561 ms/op
                 createUser·p1.00:   22.118 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 298743
  mean =      3.211 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20958 
    [ 2.500,  5.000) = 273724 
    [ 5.000,  7.500) = 3247 
    [ 7.500, 10.000) = 409 
    [10.000, 12.500) = 71 
    [12.500, 15.000) = 14 
    [15.000, 17.500) = 56 
    [17.500, 20.000) = 120 
    [20.000, 22.500) = 126 
    [22.500, 25.000) = 17 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.331 ms/op
     p(50.0000) =      3.183 ms/op
     p(90.0000) =      3.478 ms/op
     p(95.0000) =      3.764 ms/op
     p(99.0000) =      5.439 ms/op
     p(99.9000) =     16.106 ms/op
     p(99.9900) =     22.057 ms/op
     p(99.9990) =     24.676 ms/op
     p(99.9999) =     25.002 ms/op
    p(100.0000) =     25.002 ms/op


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
# Warmup Iteration   1: 7.534 ±(99.9%) 0.087 ms/op
# Warmup Iteration   2: 3.485 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.245 ±(99.9%) 0.008 ms/op
Iteration   1: 3.285 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.606 ms/op
                 existUser·p0.50:   3.162 ms/op
                 existUser·p0.90:   3.781 ms/op
                 existUser·p0.95:   4.153 ms/op
                 existUser·p0.99:   5.743 ms/op
                 existUser·p0.999:  13.894 ms/op
                 existUser·p0.9999: 29.058 ms/op
                 existUser·p1.00:   29.688 ms/op

Iteration   2: 3.171 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.612 ms/op
                 existUser·p0.50:   3.047 ms/op
                 existUser·p0.90:   3.498 ms/op
                 existUser·p0.95:   4.211 ms/op
                 existUser·p0.99:   5.677 ms/op
                 existUser·p0.999:  12.321 ms/op
                 existUser·p0.9999: 25.494 ms/op
                 existUser·p1.00:   26.640 ms/op

Iteration   3: 3.115 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.010 ms/op
                 existUser·p0.50:   3.047 ms/op
                 existUser·p0.90:   3.367 ms/op
                 existUser·p0.95:   3.621 ms/op
                 existUser·p0.99:   5.382 ms/op
                 existUser·p0.999:  10.025 ms/op
                 existUser·p0.9999: 23.421 ms/op
                 existUser·p1.00:   25.297 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 300818
  mean =      3.189 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13689 
    [ 2.500,  5.000) = 280681 
    [ 5.000,  7.500) = 5448 
    [ 7.500, 10.000) = 576 
    [10.000, 12.500) = 128 
    [12.500, 15.000) = 8 
    [15.000, 17.500) = 4 
    [17.500, 20.000) = 95 
    [20.000, 22.500) = 42 
    [22.500, 25.000) = 96 
    [25.000, 27.500) = 31 

  Percentiles, ms/op:
      p(0.0000) =      0.612 ms/op
     p(50.0000) =      3.088 ms/op
     p(90.0000) =      3.559 ms/op
     p(95.0000) =      4.108 ms/op
     p(99.0000) =      5.612 ms/op
     p(99.9000) =     12.321 ms/op
     p(99.9900) =     27.028 ms/op
     p(99.9990) =     29.425 ms/op
     p(99.9999) =     29.688 ms/op
    p(100.0000) =     29.688 ms/op


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
# Warmup Iteration   1: 8.494 ±(99.9%) 0.093 ms/op
# Warmup Iteration   2: 3.541 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.314 ±(99.9%) 0.010 ms/op
Iteration   1: 3.297 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.825 ms/op
                 getUser·p0.50:   3.187 ms/op
                 getUser·p0.90:   3.756 ms/op
                 getUser·p0.95:   4.284 ms/op
                 getUser·p0.99:   5.956 ms/op
                 getUser·p0.999:  17.663 ms/op
                 getUser·p0.9999: 23.439 ms/op
                 getUser·p1.00:   24.412 ms/op

Iteration   2: 3.274 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.153 ms/op
                 getUser·p0.50:   3.146 ms/op
                 getUser·p0.90:   3.629 ms/op
                 getUser·p0.95:   4.391 ms/op
                 getUser·p0.99:   6.029 ms/op
                 getUser·p0.999:  13.701 ms/op
                 getUser·p0.9999: 23.338 ms/op
                 getUser·p1.00:   23.822 ms/op

Iteration   3: 3.196 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.335 ms/op
                 getUser·p0.50:   3.105 ms/op
                 getUser·p0.90:   3.486 ms/op
                 getUser·p0.95:   3.641 ms/op
                 getUser·p0.99:   5.554 ms/op
                 getUser·p0.999:  13.550 ms/op
                 getUser·p0.9999: 21.365 ms/op
                 getUser·p1.00:   22.381 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 294770
  mean =      3.255 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12399 
    [ 2.500,  5.000) = 274908 
    [ 5.000,  7.500) = 6540 
    [ 7.500, 10.000) = 397 
    [10.000, 12.500) = 116 
    [12.500, 15.000) = 76 
    [15.000, 17.500) = 70 
    [17.500, 20.000) = 72 
    [20.000, 22.500) = 137 
    [22.500, 25.000) = 55 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.153 ms/op
     p(50.0000) =      3.150 ms/op
     p(90.0000) =      3.613 ms/op
     p(95.0000) =      4.010 ms/op
     p(99.0000) =      5.784 ms/op
     p(99.9000) =     16.269 ms/op
     p(99.9900) =     22.970 ms/op
     p(99.9990) =     24.348 ms/op
     p(99.9999) =     24.412 ms/op
    p(100.0000) =     24.412 ms/op


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
# Warmup Iteration   1: 9.481 ±(99.9%) 0.119 ms/op
# Warmup Iteration   2: 4.154 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.817 ±(99.9%) 0.011 ms/op
Iteration   1: 3.914 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.093 ms/op
                 listUser·p0.50:   3.797 ms/op
                 listUser·p0.90:   4.276 ms/op
                 listUser·p0.95:   4.858 ms/op
                 listUser·p0.99:   7.619 ms/op
                 listUser·p0.999:  16.283 ms/op
                 listUser·p0.9999: 20.185 ms/op
                 listUser·p1.00:   21.398 ms/op

Iteration   2: 3.779 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.468 ms/op
                 listUser·p0.50:   3.641 ms/op
                 listUser·p0.90:   4.088 ms/op
                 listUser·p0.95:   4.645 ms/op
                 listUser·p0.99:   6.562 ms/op
                 listUser·p0.999:  13.719 ms/op
                 listUser·p0.9999: 21.579 ms/op
                 listUser·p1.00:   21.627 ms/op

Iteration   3: 3.798 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.396 ms/op
                 listUser·p0.50:   3.736 ms/op
                 listUser·p0.90:   4.096 ms/op
                 listUser·p0.95:   4.448 ms/op
                 listUser·p0.99:   6.885 ms/op
                 listUser·p0.999:  13.418 ms/op
                 listUser·p0.9999: 17.662 ms/op
                 listUser·p1.00:   18.383 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 250588
  mean =      3.829 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 48 
    [ 2.500,  5.000) = 241436 
    [ 5.000,  7.500) = 7114 
    [ 7.500, 10.000) = 1343 
    [10.000, 12.500) = 225 
    [12.500, 15.000) = 194 
    [15.000, 17.500) = 116 
    [17.500, 20.000) = 72 
    [20.000, 22.500) = 40 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.468 ms/op
     p(50.0000) =      3.744 ms/op
     p(90.0000) =      4.170 ms/op
     p(95.0000) =      4.620 ms/op
     p(99.0000) =      6.930 ms/op
     p(99.9000) =     14.677 ms/op
     p(99.9900) =     20.480 ms/op
     p(99.9990) =     21.610 ms/op
     p(99.9999) =     21.627 ms/op
    p(100.0000) =     21.627 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.777 ± 1.032  ops/ms
ClientPb.existUser                       thrpt       3  10.188 ± 4.258  ops/ms
ClientPb.getUser                         thrpt       3   9.559 ± 2.796  ops/ms
ClientPb.listUser                        thrpt       3   8.302 ± 2.544  ops/ms
ClientPb.createUser                       avgt       3   3.298 ± 1.763   ms/op
ClientPb.existUser                        avgt       3   3.150 ± 1.769   ms/op
ClientPb.getUser                          avgt       3   3.227 ± 0.407   ms/op
ClientPb.listUser                         avgt       3   3.780 ± 1.156   ms/op
ClientPb.createUser                     sample  298743   3.211 ± 0.004   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.331           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.183           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.478           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.764           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.439           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.106           ms/op
ClientPb.createUser:createUser·p0.9999  sample          22.057           ms/op
ClientPb.createUser:createUser·p1.00    sample          25.002           ms/op
ClientPb.existUser                      sample  300818   3.189 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.612           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.088           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.559           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.108           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.612           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.321           ms/op
ClientPb.existUser:existUser·p0.9999    sample          27.028           ms/op
ClientPb.existUser:existUser·p1.00      sample          29.688           ms/op
ClientPb.getUser                        sample  294770   3.255 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.153           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.150           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.613           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.010           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.784           ms/op
ClientPb.getUser:getUser·p0.999         sample          16.269           ms/op
ClientPb.getUser:getUser·p0.9999        sample          22.970           ms/op
ClientPb.getUser:getUser·p1.00          sample          24.412           ms/op
ClientPb.listUser                       sample  250588   3.829 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.468           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.744           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.170           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.620           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.930           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.677           ms/op
ClientPb.listUser:listUser·p0.9999      sample          20.480           ms/op
ClientPb.listUser:listUser·p1.00        sample          21.627           ms/op
