# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.480 ops/ms
# Warmup Iteration   2: 6.226 ops/ms
# Warmup Iteration   3: 9.610 ops/ms
Iteration   1: 9.910 ops/ms
Iteration   2: 10.246 ops/ms
Iteration   3: 10.398 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  10.185 ±(99.9%) 4.557 ops/ms [Average]
  (min, avg, max) = (9.910, 10.185, 10.398), stdev = 0.250
  CI (99.9%): [5.628, 14.742] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 3.852 ops/ms
# Warmup Iteration   2: 9.808 ops/ms
# Warmup Iteration   3: 10.150 ops/ms
Iteration   1: 10.676 ops/ms
Iteration   2: 10.460 ops/ms
Iteration   3: 9.916 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.350 ±(99.9%) 7.144 ops/ms [Average]
  (min, avg, max) = (9.916, 10.350, 10.676), stdev = 0.392
  CI (99.9%): [3.206, 17.495] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.468 ops/ms
# Warmup Iteration   2: 9.058 ops/ms
# Warmup Iteration   3: 9.908 ops/ms
Iteration   1: 10.264 ops/ms
Iteration   2: 10.155 ops/ms
Iteration   3: 10.148 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.189 ±(99.9%) 1.192 ops/ms [Average]
  (min, avg, max) = (10.148, 10.189, 10.264), stdev = 0.065
  CI (99.9%): [8.997, 11.381] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 3.520 ops/ms
# Warmup Iteration   2: 7.430 ops/ms
# Warmup Iteration   3: 8.727 ops/ms
Iteration   1: 8.700 ops/ms
Iteration   2: 8.903 ops/ms
Iteration   3: 8.597 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.734 ±(99.9%) 2.841 ops/ms [Average]
  (min, avg, max) = (8.597, 8.734, 8.903), stdev = 0.156
  CI (99.9%): [5.893, 11.574] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 7.736 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.430 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.290 ±(99.9%) 0.003 ms/op
Iteration   1: 3.182 ±(99.9%) 0.005 ms/op
Iteration   2: 3.168 ±(99.9%) 0.005 ms/op
Iteration   3: 3.289 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.213 ±(99.9%) 1.211 ms/op [Average]
  (min, avg, max) = (3.168, 3.213, 3.289), stdev = 0.066
  CI (99.9%): [2.002, 4.423] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 7.230 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.265 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.256 ±(99.9%) 0.005 ms/op
Iteration   1: 3.174 ±(99.9%) 0.006 ms/op
Iteration   2: 3.161 ±(99.9%) 0.003 ms/op
Iteration   3: 2.953 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.096 ±(99.9%) 2.263 ms/op [Average]
  (min, avg, max) = (2.953, 3.096, 3.174), stdev = 0.124
  CI (99.9%): [0.833, 5.359] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 7.089 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.433 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.292 ±(99.9%) 0.003 ms/op
Iteration   1: 3.195 ±(99.9%) 0.005 ms/op
Iteration   2: 3.200 ±(99.9%) 0.007 ms/op
Iteration   3: 3.225 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.207 ±(99.9%) 0.293 ms/op [Average]
  (min, avg, max) = (3.195, 3.207, 3.225), stdev = 0.016
  CI (99.9%): [2.914, 3.500] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 8.129 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.987 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.691 ±(99.9%) 0.006 ms/op
Iteration   1: 3.741 ±(99.9%) 0.004 ms/op
Iteration   2: 3.709 ±(99.9%) 0.006 ms/op
Iteration   3: 3.763 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.737 ±(99.9%) 0.495 ms/op [Average]
  (min, avg, max) = (3.709, 3.737, 3.763), stdev = 0.027
  CI (99.9%): [3.242, 4.233] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 8.285 ±(99.9%) 0.097 ms/op
# Warmup Iteration   2: 3.626 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.389 ±(99.9%) 0.009 ms/op
Iteration   1: 3.137 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.231 ms/op
                 createUser·p0.50:   3.019 ms/op
                 createUser·p0.90:   3.543 ms/op
                 createUser·p0.95:   3.772 ms/op
                 createUser·p0.99:   5.259 ms/op
                 createUser·p0.999:  10.437 ms/op
                 createUser·p0.9999: 19.687 ms/op
                 createUser·p1.00:   20.578 ms/op

Iteration   2: 3.220 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.174 ms/op
                 createUser·p0.50:   3.154 ms/op
                 createUser·p0.90:   3.568 ms/op
                 createUser·p0.95:   4.088 ms/op
                 createUser·p0.99:   5.521 ms/op
                 createUser·p0.999:  20.972 ms/op
                 createUser·p0.9999: 30.004 ms/op
                 createUser·p1.00:   31.883 ms/op

Iteration   3: 3.355 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.432 ms/op
                 createUser·p0.50:   3.265 ms/op
                 createUser·p0.90:   3.854 ms/op
                 createUser·p0.95:   4.252 ms/op
                 createUser·p0.99:   5.661 ms/op
                 createUser·p0.999:  14.026 ms/op
                 createUser·p0.9999: 19.447 ms/op
                 createUser·p1.00:   19.825 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 296632
  mean =      3.235 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19184 
    [ 2.500,  5.000) = 270280 
    [ 5.000,  7.500) = 6539 
    [ 7.500, 10.000) = 231 
    [10.000, 12.500) = 46 
    [12.500, 15.000) = 36 
    [15.000, 17.500) = 33 
    [17.500, 20.000) = 153 
    [20.000, 22.500) = 66 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 26 
    [27.500, 30.000) = 29 
    [30.000, 32.500) = 9 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.174 ms/op
     p(50.0000) =      3.174 ms/op
     p(90.0000) =      3.686 ms/op
     p(95.0000) =      4.018 ms/op
     p(99.0000) =      5.439 ms/op
     p(99.9000) =     16.335 ms/op
     p(99.9900) =     29.109 ms/op
     p(99.9990) =     30.773 ms/op
     p(99.9999) =     31.883 ms/op
    p(100.0000) =     31.883 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 6.661 ±(99.9%) 0.079 ms/op
# Warmup Iteration   2: 3.381 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.119 ±(99.9%) 0.008 ms/op
Iteration   1: 3.024 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.440 ms/op
                 existUser·p0.50:   3.006 ms/op
                 existUser·p0.90:   3.191 ms/op
                 existUser·p0.95:   3.416 ms/op
                 existUser·p0.99:   5.276 ms/op
                 existUser·p0.999:  8.471 ms/op
                 existUser·p0.9999: 24.379 ms/op
                 existUser·p1.00:   25.199 ms/op

Iteration   2: 3.037 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.346 ms/op
                 existUser·p0.50:   3.043 ms/op
                 existUser·p0.90:   3.174 ms/op
                 existUser·p0.95:   3.252 ms/op
                 existUser·p0.99:   5.202 ms/op
                 existUser·p0.999:  12.272 ms/op
                 existUser·p0.9999: 22.002 ms/op
                 existUser·p1.00:   22.446 ms/op

Iteration   3: 3.083 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   1.171 ms/op
                 existUser·p0.50:   2.998 ms/op
                 existUser·p0.90:   3.412 ms/op
                 existUser·p0.95:   3.666 ms/op
                 existUser·p0.99:   5.210 ms/op
                 existUser·p0.999:  8.847 ms/op
                 existUser·p0.9999: 20.120 ms/op
                 existUser·p1.00:   21.103 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 314815
  mean =      3.048 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22529 
    [ 2.500,  5.000) = 288027 
    [ 5.000,  7.500) = 3711 
    [ 7.500, 10.000) = 191 
    [10.000, 12.500) = 64 
    [12.500, 15.000) = 23 
    [15.000, 17.500) = 46 
    [17.500, 20.000) = 60 
    [20.000, 22.500) = 109 
    [22.500, 25.000) = 53 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.171 ms/op
     p(50.0000) =      3.019 ms/op
     p(90.0000) =      3.252 ms/op
     p(95.0000) =      3.494 ms/op
     p(99.0000) =      5.235 ms/op
     p(99.9000) =     11.792 ms/op
     p(99.9900) =     23.413 ms/op
     p(99.9990) =     24.927 ms/op
     p(99.9999) =     25.199 ms/op
    p(100.0000) =     25.199 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 8.105 ±(99.9%) 0.098 ms/op
# Warmup Iteration   2: 3.407 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.248 ±(99.9%) 0.010 ms/op
Iteration   1: 3.194 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.130 ms/op
                 getUser·p0.50:   3.072 ms/op
                 getUser·p0.90:   3.576 ms/op
                 getUser·p0.95:   4.325 ms/op
                 getUser·p0.99:   6.152 ms/op
                 getUser·p0.999:  17.072 ms/op
                 getUser·p0.9999: 19.101 ms/op
                 getUser·p1.00:   20.513 ms/op

Iteration   2: 3.082 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.202 ms/op
                 getUser·p0.50:   2.982 ms/op
                 getUser·p0.90:   3.363 ms/op
                 getUser·p0.95:   3.514 ms/op
                 getUser·p0.99:   5.276 ms/op
                 getUser·p0.999:  17.859 ms/op
                 getUser·p0.9999: 21.724 ms/op
                 getUser·p1.00:   22.872 ms/op

Iteration   3: 3.202 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.159 ms/op
                 getUser·p0.50:   3.039 ms/op
                 getUser·p0.90:   3.527 ms/op
                 getUser·p0.95:   4.448 ms/op
                 getUser·p0.99:   5.863 ms/op
                 getUser·p0.999:  12.924 ms/op
                 getUser·p0.9999: 17.859 ms/op
                 getUser·p1.00:   18.448 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 303839
  mean =      3.158 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9244 
    [ 2.500,  5.000) = 287342 
    [ 5.000,  7.500) = 6377 
    [ 7.500, 10.000) = 435 
    [10.000, 12.500) = 73 
    [12.500, 15.000) = 18 
    [15.000, 17.500) = 133 
    [17.500, 20.000) = 184 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.130 ms/op
     p(50.0000) =      3.031 ms/op
     p(90.0000) =      3.469 ms/op
     p(95.0000) =      4.157 ms/op
     p(99.0000) =      5.734 ms/op
     p(99.9000) =     16.531 ms/op
     p(99.9900) =     20.041 ms/op
     p(99.9990) =     22.445 ms/op
     p(99.9999) =     22.872 ms/op
    p(100.0000) =     22.872 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 9.807 ±(99.9%) 0.117 ms/op
# Warmup Iteration   2: 4.222 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.777 ±(99.9%) 0.011 ms/op
Iteration   1: 3.694 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.191 ms/op
                 listUser·p0.50:   3.543 ms/op
                 listUser·p0.90:   3.981 ms/op
                 listUser·p0.95:   4.219 ms/op
                 listUser·p0.99:   7.258 ms/op
                 listUser·p0.999:  15.122 ms/op
                 listUser·p0.9999: 19.148 ms/op
                 listUser·p1.00:   20.251 ms/op

Iteration   2: 3.752 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.200 ms/op
                 listUser·p0.50:   3.662 ms/op
                 listUser·p0.90:   4.006 ms/op
                 listUser·p0.95:   4.211 ms/op
                 listUser·p0.99:   7.381 ms/op
                 listUser·p0.999:  13.926 ms/op
                 listUser·p0.9999: 14.778 ms/op
                 listUser·p1.00:   15.630 ms/op

Iteration   3: 3.658 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.253 ms/op
                 listUser·p0.50:   3.502 ms/op
                 listUser·p0.90:   3.928 ms/op
                 listUser·p0.95:   4.178 ms/op
                 listUser·p0.99:   7.021 ms/op
                 listUser·p0.999:  13.337 ms/op
                 listUser·p0.9999: 14.308 ms/op
                 listUser·p1.00:   14.647 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 259126
  mean =      3.701 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 89 
    [ 2.500,  5.000) = 251099 
    [ 5.000,  7.500) = 5783 
    [ 7.500, 10.000) = 1274 
    [10.000, 12.500) = 429 
    [12.500, 15.000) = 353 
    [15.000, 17.500) = 28 
    [17.500, 20.000) = 68 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.191 ms/op
     p(50.0000) =      3.555 ms/op
     p(90.0000) =      3.977 ms/op
     p(95.0000) =      4.202 ms/op
     p(99.0000) =      7.225 ms/op
     p(99.9000) =     13.973 ms/op
     p(99.9900) =     18.809 ms/op
     p(99.9990) =     20.067 ms/op
     p(99.9999) =     20.251 ms/op
    p(100.0000) =     20.251 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  10.185 ± 4.557  ops/ms
ClientPb.existUser                       thrpt       3  10.350 ± 7.144  ops/ms
ClientPb.getUser                         thrpt       3  10.189 ± 1.192  ops/ms
ClientPb.listUser                        thrpt       3   8.734 ± 2.841  ops/ms
ClientPb.createUser                       avgt       3   3.213 ± 1.211   ms/op
ClientPb.existUser                        avgt       3   3.096 ± 2.263   ms/op
ClientPb.getUser                          avgt       3   3.207 ± 0.293   ms/op
ClientPb.listUser                         avgt       3   3.737 ± 0.495   ms/op
ClientPb.createUser                     sample  296632   3.235 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.174           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.174           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.686           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.018           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.439           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.335           ms/op
ClientPb.createUser:createUser·p0.9999  sample          29.109           ms/op
ClientPb.createUser:createUser·p1.00    sample          31.883           ms/op
ClientPb.existUser                      sample  314815   3.048 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.171           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.019           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.252           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.494           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.235           ms/op
ClientPb.existUser:existUser·p0.999     sample          11.792           ms/op
ClientPb.existUser:existUser·p0.9999    sample          23.413           ms/op
ClientPb.existUser:existUser·p1.00      sample          25.199           ms/op
ClientPb.getUser                        sample  303839   3.158 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.130           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.031           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.469           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.157           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.734           ms/op
ClientPb.getUser:getUser·p0.999         sample          16.531           ms/op
ClientPb.getUser:getUser·p0.9999        sample          20.041           ms/op
ClientPb.getUser:getUser·p1.00          sample          22.872           ms/op
ClientPb.listUser                       sample  259126   3.701 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.191           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.555           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.977           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.202           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.225           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.973           ms/op
ClientPb.listUser:listUser·p0.9999      sample          18.809           ms/op
ClientPb.listUser:listUser·p1.00        sample          20.251           ms/op
