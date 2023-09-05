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
# Warmup Iteration   1: 2.589 ops/ms
# Warmup Iteration   2: 6.465 ops/ms
# Warmup Iteration   3: 9.040 ops/ms
Iteration   1: 9.631 ops/ms
Iteration   2: 9.865 ops/ms
Iteration   3: 9.582 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.692 ±(99.9%) 2.763 ops/ms [Average]
  (min, avg, max) = (9.582, 9.692, 9.865), stdev = 0.151
  CI (99.9%): [6.929, 12.456] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 3.619 ops/ms
# Warmup Iteration   2: 9.533 ops/ms
# Warmup Iteration   3: 9.522 ops/ms
Iteration   1: 10.158 ops/ms
Iteration   2: 10.261 ops/ms
Iteration   3: 10.210 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.210 ±(99.9%) 0.936 ops/ms [Average]
  (min, avg, max) = (10.158, 10.210, 10.261), stdev = 0.051
  CI (99.9%): [9.274, 11.145] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.390 ops/ms
# Warmup Iteration   2: 8.861 ops/ms
# Warmup Iteration   3: 9.961 ops/ms
Iteration   1: 9.782 ops/ms
Iteration   2: 9.989 ops/ms
Iteration   3: 9.749 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.840 ±(99.9%) 2.376 ops/ms [Average]
  (min, avg, max) = (9.749, 9.840, 9.989), stdev = 0.130
  CI (99.9%): [7.464, 12.216] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.789 ops/ms
# Warmup Iteration   2: 7.710 ops/ms
# Warmup Iteration   3: 7.886 ops/ms
Iteration   1: 8.397 ops/ms
Iteration   2: 8.529 ops/ms
Iteration   3: 8.183 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.370 ±(99.9%) 3.184 ops/ms [Average]
  (min, avg, max) = (8.183, 8.370, 8.529), stdev = 0.175
  CI (99.9%): [5.186, 11.553] (assumes normal distribution)


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
# Warmup Iteration   1: 8.504 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.601 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.393 ±(99.9%) 0.004 ms/op
Iteration   1: 3.370 ±(99.9%) 0.007 ms/op
Iteration   2: 3.240 ±(99.9%) 0.007 ms/op
Iteration   3: 3.274 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.295 ±(99.9%) 1.237 ms/op [Average]
  (min, avg, max) = (3.240, 3.295, 3.370), stdev = 0.068
  CI (99.9%): [2.057, 4.532] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 6.602 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.424 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.244 ±(99.9%) 0.005 ms/op
Iteration   1: 3.257 ±(99.9%) 0.003 ms/op
Iteration   2: 3.161 ±(99.9%) 0.004 ms/op
Iteration   3: 3.055 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.158 ±(99.9%) 1.844 ms/op [Average]
  (min, avg, max) = (3.055, 3.158, 3.257), stdev = 0.101
  CI (99.9%): [1.314, 5.001] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 8.124 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.439 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.309 ±(99.9%) 0.003 ms/op
Iteration   1: 3.275 ±(99.9%) 0.004 ms/op
Iteration   2: 3.133 ±(99.9%) 0.002 ms/op
Iteration   3: 3.286 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.231 ±(99.9%) 1.552 ms/op [Average]
  (min, avg, max) = (3.133, 3.231, 3.286), stdev = 0.085
  CI (99.9%): [1.679, 4.783] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 9.583 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 4.385 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.932 ±(99.9%) 0.004 ms/op
Iteration   1: 3.778 ±(99.9%) 0.007 ms/op
Iteration   2: 3.800 ±(99.9%) 0.007 ms/op
Iteration   3: 3.758 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.779 ±(99.9%) 0.385 ms/op [Average]
  (min, avg, max) = (3.758, 3.779, 3.800), stdev = 0.021
  CI (99.9%): [3.394, 4.164] (assumes normal distribution)


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
# Warmup Iteration   1: 8.060 ±(99.9%) 0.091 ms/op
# Warmup Iteration   2: 3.735 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.292 ±(99.9%) 0.009 ms/op
Iteration   1: 3.280 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.935 ms/op
                 createUser·p0.50:   3.203 ms/op
                 createUser·p0.90:   3.670 ms/op
                 createUser·p0.95:   4.149 ms/op
                 createUser·p0.99:   6.054 ms/op
                 createUser·p0.999:  12.358 ms/op
                 createUser·p0.9999: 21.209 ms/op
                 createUser·p1.00:   21.561 ms/op

Iteration   2: 3.316 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.614 ms/op
                 createUser·p0.50:   3.224 ms/op
                 createUser·p0.90:   3.748 ms/op
                 createUser·p0.95:   4.211 ms/op
                 createUser·p0.99:   6.423 ms/op
                 createUser·p0.999:  17.184 ms/op
                 createUser·p0.9999: 22.949 ms/op
                 createUser·p1.00:   23.364 ms/op

Iteration   3: 3.312 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.581 ms/op
                 createUser·p0.50:   3.092 ms/op
                 createUser·p0.90:   3.981 ms/op
                 createUser·p0.95:   4.456 ms/op
                 createUser·p0.99:   5.923 ms/op
                 createUser·p0.999:  18.481 ms/op
                 createUser·p0.9999: 23.386 ms/op
                 createUser·p1.00:   27.132 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 290641
  mean =      3.303 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14802 
    [ 2.500,  5.000) = 267505 
    [ 5.000,  7.500) = 6656 
    [ 7.500, 10.000) = 1042 
    [10.000, 12.500) = 202 
    [12.500, 15.000) = 60 
    [15.000, 17.500) = 110 
    [17.500, 20.000) = 127 
    [20.000, 22.500) = 105 
    [22.500, 25.000) = 24 
    [25.000, 27.500) = 8 

  Percentiles, ms/op:
      p(0.0000) =      0.935 ms/op
     p(50.0000) =      3.187 ms/op
     p(90.0000) =      3.781 ms/op
     p(95.0000) =      4.375 ms/op
     p(99.0000) =      6.116 ms/op
     p(99.9000) =     16.515 ms/op
     p(99.9900) =     22.544 ms/op
     p(99.9990) =     25.616 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 7.454 ±(99.9%) 0.093 ms/op
# Warmup Iteration   2: 3.412 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.145 ±(99.9%) 0.008 ms/op
Iteration   1: 3.285 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.487 ms/op
                 existUser·p0.50:   3.183 ms/op
                 existUser·p0.90:   3.781 ms/op
                 existUser·p0.95:   4.252 ms/op
                 existUser·p0.99:   5.890 ms/op
                 existUser·p0.999:  16.122 ms/op
                 existUser·p0.9999: 27.075 ms/op
                 existUser·p1.00:   29.065 ms/op

Iteration   2: 3.150 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.419 ms/op
                 existUser·p0.50:   3.006 ms/op
                 existUser·p0.90:   3.457 ms/op
                 existUser·p0.95:   3.867 ms/op
                 existUser·p0.99:   5.871 ms/op
                 existUser·p0.999:  11.026 ms/op
                 existUser·p0.9999: 21.692 ms/op
                 existUser·p1.00:   23.560 ms/op

Iteration   3: 3.167 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.090 ms/op
                 existUser·p0.50:   3.027 ms/op
                 existUser·p0.90:   3.453 ms/op
                 existUser·p0.95:   4.317 ms/op
                 existUser·p0.99:   5.513 ms/op
                 existUser·p0.999:  10.574 ms/op
                 existUser·p0.9999: 26.313 ms/op
                 existUser·p1.00:   27.263 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 300026
  mean =      3.199 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14134 
    [ 2.500,  5.000) = 278549 
    [ 5.000,  7.500) = 6061 
    [ 7.500, 10.000) = 803 
    [10.000, 12.500) = 158 
    [12.500, 15.000) = 5 
    [15.000, 17.500) = 28 
    [17.500, 20.000) = 63 
    [20.000, 22.500) = 144 
    [22.500, 25.000) = 20 
    [25.000, 27.500) = 55 

  Percentiles, ms/op:
      p(0.0000) =      1.090 ms/op
     p(50.0000) =      3.101 ms/op
     p(90.0000) =      3.551 ms/op
     p(95.0000) =      4.149 ms/op
     p(99.0000) =      5.767 ms/op
     p(99.9000) =     15.595 ms/op
     p(99.9900) =     26.214 ms/op
     p(99.9990) =     28.606 ms/op
     p(99.9999) =     29.065 ms/op
    p(100.0000) =     29.065 ms/op


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
# Warmup Iteration   1: 7.534 ±(99.9%) 0.092 ms/op
# Warmup Iteration   2: 3.661 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.310 ±(99.9%) 0.010 ms/op
Iteration   1: 3.279 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.503 ms/op
                 getUser·p0.50:   3.133 ms/op
                 getUser·p0.90:   3.723 ms/op
                 getUser·p0.95:   4.301 ms/op
                 getUser·p0.99:   6.963 ms/op
                 getUser·p0.999:  17.250 ms/op
                 getUser·p0.9999: 20.742 ms/op
                 getUser·p1.00:   21.135 ms/op

Iteration   2: 3.243 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.288 ms/op
                 getUser·p0.50:   3.142 ms/op
                 getUser·p0.90:   3.695 ms/op
                 getUser·p0.95:   4.039 ms/op
                 getUser·p0.99:   5.703 ms/op
                 getUser·p0.999:  10.519 ms/op
                 getUser·p0.9999: 21.238 ms/op
                 getUser·p1.00:   21.627 ms/op

Iteration   3: 3.347 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.694 ms/op
                 getUser·p0.50:   3.199 ms/op
                 getUser·p0.90:   4.039 ms/op
                 getUser·p0.95:   4.563 ms/op
                 getUser·p0.99:   6.349 ms/op
                 getUser·p0.999:  14.106 ms/op
                 getUser·p0.9999: 20.808 ms/op
                 getUser·p1.00:   22.217 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 291825
  mean =      3.289 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17229 
    [ 2.500,  5.000) = 265588 
    [ 5.000,  7.500) = 7287 
    [ 7.500, 10.000) = 1151 
    [10.000, 12.500) = 177 
    [12.500, 15.000) = 79 
    [15.000, 17.500) = 82 
    [17.500, 20.000) = 115 
    [20.000, 22.500) = 117 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.288 ms/op
     p(50.0000) =      3.154 ms/op
     p(90.0000) =      3.777 ms/op
     p(95.0000) =      4.383 ms/op
     p(99.0000) =      6.396 ms/op
     p(99.9000) =     15.661 ms/op
     p(99.9900) =     21.037 ms/op
     p(99.9990) =     21.659 ms/op
     p(99.9999) =     22.217 ms/op
    p(100.0000) =     22.217 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 9.438 ±(99.9%) 0.129 ms/op
# Warmup Iteration   2: 4.212 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.888 ±(99.9%) 0.012 ms/op
Iteration   1: 3.903 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.626 ms/op
                 listUser·p0.50:   3.715 ms/op
                 listUser·p0.90:   4.407 ms/op
                 listUser·p0.95:   4.743 ms/op
                 listUser·p0.99:   7.570 ms/op
                 listUser·p0.999:  15.499 ms/op
                 listUser·p0.9999: 26.699 ms/op
                 listUser·p1.00:   27.132 ms/op

Iteration   2: 3.964 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.204 ms/op
                 listUser·p0.50:   3.842 ms/op
                 listUser·p0.90:   4.268 ms/op
                 listUser·p0.95:   4.604 ms/op
                 listUser·p0.99:   8.200 ms/op
                 listUser·p0.999:  12.468 ms/op
                 listUser·p0.9999: 15.630 ms/op
                 listUser·p1.00:   15.647 ms/op

Iteration   3: 3.837 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.413 ms/op
                 listUser·p0.50:   3.723 ms/op
                 listUser·p0.90:   4.317 ms/op
                 listUser·p0.95:   4.588 ms/op
                 listUser·p0.99:   7.240 ms/op
                 listUser·p0.999:  13.566 ms/op
                 listUser·p0.9999: 15.254 ms/op
                 listUser·p1.00:   15.335 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 246066
  mean =      3.900 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 36 
    [ 2.500,  5.000) = 236608 
    [ 5.000,  7.500) = 6396 
    [ 7.500, 10.000) = 2292 
    [10.000, 12.500) = 370 
    [12.500, 15.000) = 223 
    [15.000, 17.500) = 88 
    [17.500, 20.000) = 21 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 21 

  Percentiles, ms/op:
      p(0.0000) =      1.626 ms/op
     p(50.0000) =      3.740 ms/op
     p(90.0000) =      4.325 ms/op
     p(95.0000) =      4.645 ms/op
     p(99.0000) =      7.875 ms/op
     p(99.9000) =     13.107 ms/op
     p(99.9900) =     24.897 ms/op
     p(99.9990) =     26.920 ms/op
     p(99.9999) =     27.132 ms/op
    p(100.0000) =     27.132 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.692 ± 2.763  ops/ms
ClientPb.existUser                       thrpt       3  10.210 ± 0.936  ops/ms
ClientPb.getUser                         thrpt       3   9.840 ± 2.376  ops/ms
ClientPb.listUser                        thrpt       3   8.370 ± 3.184  ops/ms
ClientPb.createUser                       avgt       3   3.295 ± 1.237   ms/op
ClientPb.existUser                        avgt       3   3.158 ± 1.844   ms/op
ClientPb.getUser                          avgt       3   3.231 ± 1.552   ms/op
ClientPb.listUser                         avgt       3   3.779 ± 0.385   ms/op
ClientPb.createUser                     sample  290641   3.303 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.935           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.187           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.781           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.375           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.116           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.515           ms/op
ClientPb.createUser:createUser·p0.9999  sample          22.544           ms/op
ClientPb.createUser:createUser·p1.00    sample          27.132           ms/op
ClientPb.existUser                      sample  300026   3.199 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.090           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.101           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.551           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.149           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.767           ms/op
ClientPb.existUser:existUser·p0.999     sample          15.595           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.214           ms/op
ClientPb.existUser:existUser·p1.00      sample          29.065           ms/op
ClientPb.getUser                        sample  291825   3.289 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.288           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.154           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.777           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.383           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.396           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.661           ms/op
ClientPb.getUser:getUser·p0.9999        sample          21.037           ms/op
ClientPb.getUser:getUser·p1.00          sample          22.217           ms/op
ClientPb.listUser                       sample  246066   3.900 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.626           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.740           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.325           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.645           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.875           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.107           ms/op
ClientPb.listUser:listUser·p0.9999      sample          24.897           ms/op
ClientPb.listUser:listUser·p1.00        sample          27.132           ms/op
