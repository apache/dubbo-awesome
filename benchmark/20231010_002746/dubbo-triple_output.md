# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.146 ops/ms
# Warmup Iteration   2: 5.343 ops/ms
# Warmup Iteration   3: 8.346 ops/ms
Iteration   1: 9.274 ops/ms
Iteration   2: 9.078 ops/ms
Iteration   3: 9.281 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.211 ±(99.9%) 2.097 ops/ms [Average]
  (min, avg, max) = (9.078, 9.211, 9.281), stdev = 0.115
  CI (99.9%): [7.114, 11.308] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 3.420 ops/ms
# Warmup Iteration   2: 8.620 ops/ms
# Warmup Iteration   3: 9.536 ops/ms
Iteration   1: 9.793 ops/ms
Iteration   2: 9.753 ops/ms
Iteration   3: 9.927 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.824 ±(99.9%) 1.657 ops/ms [Average]
  (min, avg, max) = (9.753, 9.824, 9.927), stdev = 0.091
  CI (99.9%): [8.167, 11.481] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 2.841 ops/ms
# Warmup Iteration   2: 8.537 ops/ms
# Warmup Iteration   3: 9.193 ops/ms
Iteration   1: 9.051 ops/ms
Iteration   2: 9.307 ops/ms
Iteration   3: 9.361 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.239 ±(99.9%) 3.019 ops/ms [Average]
  (min, avg, max) = (9.051, 9.239, 9.361), stdev = 0.165
  CI (99.9%): [6.221, 12.258] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 2.560 ops/ms
# Warmup Iteration   2: 7.147 ops/ms
# Warmup Iteration   3: 7.709 ops/ms
Iteration   1: 7.686 ops/ms
Iteration   2: 7.565 ops/ms
Iteration   3: 7.723 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.658 ±(99.9%) 1.511 ops/ms [Average]
  (min, avg, max) = (7.565, 7.658, 7.723), stdev = 0.083
  CI (99.9%): [6.147, 9.169] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 10.135 ±(99.9%) 0.079 ms/op
# Warmup Iteration   2: 4.251 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.614 ±(99.9%) 0.004 ms/op
Iteration   1: 3.480 ±(99.9%) 0.005 ms/op
Iteration   2: 3.481 ±(99.9%) 0.005 ms/op
Iteration   3: 3.468 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.476 ±(99.9%) 0.130 ms/op [Average]
  (min, avg, max) = (3.468, 3.476, 3.481), stdev = 0.007
  CI (99.9%): [3.346, 3.606] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 9.755 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.653 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.392 ±(99.9%) 0.005 ms/op
Iteration   1: 3.373 ±(99.9%) 0.003 ms/op
Iteration   2: 3.372 ±(99.9%) 0.004 ms/op
Iteration   3: 3.347 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.364 ±(99.9%) 0.269 ms/op [Average]
  (min, avg, max) = (3.347, 3.364, 3.373), stdev = 0.015
  CI (99.9%): [3.095, 3.633] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 8.997 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.606 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.547 ±(99.9%) 0.005 ms/op
Iteration   1: 3.429 ±(99.9%) 0.004 ms/op
Iteration   2: 3.409 ±(99.9%) 0.006 ms/op
Iteration   3: 3.512 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.450 ±(99.9%) 0.996 ms/op [Average]
  (min, avg, max) = (3.409, 3.450, 3.512), stdev = 0.055
  CI (99.9%): [2.454, 4.446] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 9.506 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 4.424 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 4.152 ±(99.9%) 0.005 ms/op
Iteration   1: 4.192 ±(99.9%) 0.005 ms/op
Iteration   2: 4.141 ±(99.9%) 0.005 ms/op
Iteration   3: 4.004 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.112 ±(99.9%) 1.776 ms/op [Average]
  (min, avg, max) = (4.004, 4.112, 4.192), stdev = 0.097
  CI (99.9%): [2.336, 5.888] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 9.064 ±(99.9%) 0.116 ms/op
# Warmup Iteration   2: 3.890 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.539 ±(99.9%) 0.011 ms/op
Iteration   1: 3.513 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.307 ms/op
                 createUser·p0.50:   3.338 ms/op
                 createUser·p0.90:   4.088 ms/op
                 createUser·p0.95:   4.391 ms/op
                 createUser·p0.99:   6.701 ms/op
                 createUser·p0.999:  18.711 ms/op
                 createUser·p0.9999: 21.496 ms/op
                 createUser·p1.00:   21.758 ms/op

Iteration   2: 3.445 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.257 ms/op
                 createUser·p0.50:   3.285 ms/op
                 createUser·p0.90:   3.908 ms/op
                 createUser·p0.95:   4.194 ms/op
                 createUser·p0.99:   6.267 ms/op
                 createUser·p0.999:  20.125 ms/op
                 createUser·p0.9999: 25.068 ms/op
                 createUser·p1.00:   25.494 ms/op

Iteration   3: 3.575 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.108 ms/op
                 createUser·p0.50:   3.383 ms/op
                 createUser·p0.90:   4.104 ms/op
                 createUser·p0.95:   4.399 ms/op
                 createUser·p0.99:   7.274 ms/op
                 createUser·p0.999:  23.020 ms/op
                 createUser·p0.9999: 34.017 ms/op
                 createUser·p1.00:   34.275 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 273302
  mean =      3.510 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3070 
    [ 2.500,  5.000) = 263240 
    [ 5.000,  7.500) = 5292 
    [ 7.500, 10.000) = 852 
    [10.000, 12.500) = 321 
    [12.500, 15.000) = 114 
    [15.000, 17.500) = 42 
    [17.500, 20.000) = 64 
    [20.000, 22.500) = 171 
    [22.500, 25.000) = 69 
    [25.000, 27.500) = 18 
    [27.500, 30.000) = 17 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 32 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.108 ms/op
     p(50.0000) =      3.330 ms/op
     p(90.0000) =      4.035 ms/op
     p(95.0000) =      4.325 ms/op
     p(99.0000) =      6.767 ms/op
     p(99.9000) =     20.546 ms/op
     p(99.9900) =     33.281 ms/op
     p(99.9990) =     34.210 ms/op
     p(99.9999) =     34.275 ms/op
    p(100.0000) =     34.275 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 9.496 ±(99.9%) 0.119 ms/op
# Warmup Iteration   2: 3.569 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.363 ±(99.9%) 0.009 ms/op
Iteration   1: 3.449 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.985 ms/op
                 existUser·p0.50:   3.265 ms/op
                 existUser·p0.90:   3.883 ms/op
                 existUser·p0.95:   4.358 ms/op
                 existUser·p0.99:   7.078 ms/op
                 existUser·p0.999:  19.857 ms/op
                 existUser·p0.9999: 28.279 ms/op
                 existUser·p1.00:   29.295 ms/op

Iteration   2: 3.458 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.407 ms/op
                 existUser·p0.50:   3.334 ms/op
                 existUser·p0.90:   3.916 ms/op
                 existUser·p0.95:   4.268 ms/op
                 existUser·p0.99:   6.185 ms/op
                 existUser·p0.999:  20.235 ms/op
                 existUser·p0.9999: 23.814 ms/op
                 existUser·p1.00:   24.379 ms/op

Iteration   3: 3.419 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.090 ms/op
                 existUser·p0.50:   3.260 ms/op
                 existUser·p0.90:   3.785 ms/op
                 existUser·p0.95:   4.211 ms/op
                 existUser·p0.99:   7.307 ms/op
                 existUser·p0.999:  12.960 ms/op
                 existUser·p0.9999: 26.039 ms/op
                 existUser·p1.00:   26.280 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 278710
  mean =      3.442 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4097 
    [ 2.500,  5.000) = 266620 
    [ 5.000,  7.500) = 6081 
    [ 7.500, 10.000) = 1176 
    [10.000, 12.500) = 387 
    [12.500, 15.000) = 41 
    [15.000, 17.500) = 16 
    [17.500, 20.000) = 39 
    [20.000, 22.500) = 128 
    [22.500, 25.000) = 69 
    [25.000, 27.500) = 34 

  Percentiles, ms/op:
      p(0.0000) =      0.985 ms/op
     p(50.0000) =      3.289 ms/op
     p(90.0000) =      3.867 ms/op
     p(95.0000) =      4.276 ms/op
     p(99.0000) =      7.029 ms/op
     p(99.9000) =     19.366 ms/op
     p(99.9900) =     26.194 ms/op
     p(99.9990) =     29.269 ms/op
     p(99.9999) =     29.295 ms/op
    p(100.0000) =     29.295 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 10.012 ±(99.9%) 0.115 ms/op
# Warmup Iteration   2: 3.734 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.581 ±(99.9%) 0.011 ms/op
Iteration   1: 3.564 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.790 ms/op
                 getUser·p0.50:   3.351 ms/op
                 getUser·p0.90:   4.010 ms/op
                 getUser·p0.95:   5.259 ms/op
                 getUser·p0.99:   7.127 ms/op
                 getUser·p0.999:  13.989 ms/op
                 getUser·p0.9999: 21.072 ms/op
                 getUser·p1.00:   21.856 ms/op

Iteration   2: 3.585 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.270 ms/op
                 getUser·p0.50:   3.383 ms/op
                 getUser·p0.90:   3.981 ms/op
                 getUser·p0.95:   5.399 ms/op
                 getUser·p0.99:   7.102 ms/op
                 getUser·p0.999:  20.054 ms/op
                 getUser·p0.9999: 22.449 ms/op
                 getUser·p1.00:   23.364 ms/op

Iteration   3: 3.485 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.311 ms/op
                 getUser·p0.50:   3.301 ms/op
                 getUser·p0.90:   3.789 ms/op
                 getUser·p0.95:   4.366 ms/op
                 getUser·p0.99:   7.234 ms/op
                 getUser·p0.999:  22.512 ms/op
                 getUser·p0.9999: 26.182 ms/op
                 getUser·p1.00:   27.132 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 270715
  mean =      3.544 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4714 
    [ 2.500,  5.000) = 252425 
    [ 5.000,  7.500) = 11456 
    [ 7.500, 10.000) = 1155 
    [10.000, 12.500) = 326 
    [12.500, 15.000) = 225 
    [15.000, 17.500) = 92 
    [17.500, 20.000) = 88 
    [20.000, 22.500) = 134 
    [22.500, 25.000) = 75 
    [25.000, 27.500) = 25 

  Percentiles, ms/op:
      p(0.0000) =      1.270 ms/op
     p(50.0000) =      3.342 ms/op
     p(90.0000) =      3.936 ms/op
     p(95.0000) =      5.014 ms/op
     p(99.0000) =      7.143 ms/op
     p(99.9000) =     19.048 ms/op
     p(99.9900) =     24.904 ms/op
     p(99.9990) =     26.570 ms/op
     p(99.9999) =     27.132 ms/op
    p(100.0000) =     27.132 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 11.848 ±(99.9%) 0.156 ms/op
# Warmup Iteration   2: 4.612 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.308 ±(99.9%) 0.015 ms/op
Iteration   1: 4.164 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.993 ms/op
                 listUser·p0.50:   4.030 ms/op
                 listUser·p0.90:   4.522 ms/op
                 listUser·p0.95:   4.825 ms/op
                 listUser·p0.99:   7.766 ms/op
                 listUser·p0.999:  21.004 ms/op
                 listUser·p0.9999: 24.805 ms/op
                 listUser·p1.00:   27.427 ms/op

Iteration   2: 4.157 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.660 ms/op
                 listUser·p0.50:   3.949 ms/op
                 listUser·p0.90:   4.768 ms/op
                 listUser·p0.95:   5.169 ms/op
                 listUser·p0.99:   8.159 ms/op
                 listUser·p0.999:  15.353 ms/op
                 listUser·p0.9999: 18.164 ms/op
                 listUser·p1.00:   18.579 ms/op

Iteration   3: 4.222 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.118 ms/op
                 listUser·p0.50:   4.071 ms/op
                 listUser·p0.90:   4.776 ms/op
                 listUser·p0.95:   5.054 ms/op
                 listUser·p0.99:   7.361 ms/op
                 listUser·p0.999:  14.467 ms/op
                 listUser·p0.9999: 16.096 ms/op
                 listUser·p1.00:   18.743 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 229438
  mean =      4.181 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 57 
    [ 2.500,  5.000) = 217143 
    [ 5.000,  7.500) = 9411 
    [ 7.500, 10.000) = 2025 
    [10.000, 12.500) = 269 
    [12.500, 15.000) = 237 
    [15.000, 17.500) = 145 
    [17.500, 20.000) = 56 
    [20.000, 22.500) = 45 
    [22.500, 25.000) = 45 
    [25.000, 27.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.660 ms/op
     p(50.0000) =      4.010 ms/op
     p(90.0000) =      4.694 ms/op
     p(95.0000) =      5.046 ms/op
     p(99.0000) =      7.848 ms/op
     p(99.9000) =     15.993 ms/op
     p(99.9900) =     24.217 ms/op
     p(99.9990) =     26.635 ms/op
     p(99.9999) =     27.427 ms/op
    p(100.0000) =     27.427 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.211 ± 2.097  ops/ms
ClientPb.existUser                       thrpt       3   9.824 ± 1.657  ops/ms
ClientPb.getUser                         thrpt       3   9.239 ± 3.019  ops/ms
ClientPb.listUser                        thrpt       3   7.658 ± 1.511  ops/ms
ClientPb.createUser                       avgt       3   3.476 ± 0.130   ms/op
ClientPb.existUser                        avgt       3   3.364 ± 0.269   ms/op
ClientPb.getUser                          avgt       3   3.450 ± 0.996   ms/op
ClientPb.listUser                         avgt       3   4.112 ± 1.776   ms/op
ClientPb.createUser                     sample  273302   3.510 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.108           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.330           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.035           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.325           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.767           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.546           ms/op
ClientPb.createUser:createUser·p0.9999  sample          33.281           ms/op
ClientPb.createUser:createUser·p1.00    sample          34.275           ms/op
ClientPb.existUser                      sample  278710   3.442 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.985           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.289           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.867           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.276           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.029           ms/op
ClientPb.existUser:existUser·p0.999     sample          19.366           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.194           ms/op
ClientPb.existUser:existUser·p1.00      sample          29.295           ms/op
ClientPb.getUser                        sample  270715   3.544 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.270           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.342           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.936           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.014           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.143           ms/op
ClientPb.getUser:getUser·p0.999         sample          19.048           ms/op
ClientPb.getUser:getUser·p0.9999        sample          24.904           ms/op
ClientPb.getUser:getUser·p1.00          sample          27.132           ms/op
ClientPb.listUser                       sample  229438   4.181 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.660           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.010           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.694           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.046           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.848           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.993           ms/op
ClientPb.listUser:listUser·p0.9999      sample          24.217           ms/op
ClientPb.listUser:listUser·p1.00        sample          27.427           ms/op
