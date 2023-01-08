# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.055 ops/ms
# Warmup Iteration   2: 5.150 ops/ms
# Warmup Iteration   3: 8.527 ops/ms
Iteration   1: 9.237 ops/ms
Iteration   2: 9.554 ops/ms
Iteration   3: 9.587 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.459 ±(99.9%) 3.529 ops/ms [Average]
  (min, avg, max) = (9.237, 9.459, 9.587), stdev = 0.193
  CI (99.9%): [5.930, 12.988] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 3.599 ops/ms
# Warmup Iteration   2: 8.755 ops/ms
# Warmup Iteration   3: 9.536 ops/ms
Iteration   1: 9.612 ops/ms
Iteration   2: 9.553 ops/ms
Iteration   3: 9.732 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.633 ±(99.9%) 1.665 ops/ms [Average]
  (min, avg, max) = (9.553, 9.633, 9.732), stdev = 0.091
  CI (99.9%): [7.968, 11.297] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.210 ops/ms
# Warmup Iteration   2: 8.715 ops/ms
# Warmup Iteration   3: 9.601 ops/ms
Iteration   1: 9.794 ops/ms
Iteration   2: 9.470 ops/ms
Iteration   3: 9.527 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.597 ±(99.9%) 3.159 ops/ms [Average]
  (min, avg, max) = (9.470, 9.597, 9.794), stdev = 0.173
  CI (99.9%): [6.438, 12.756] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 2.998 ops/ms
# Warmup Iteration   2: 7.573 ops/ms
# Warmup Iteration   3: 7.968 ops/ms
Iteration   1: 7.846 ops/ms
Iteration   2: 8.187 ops/ms
Iteration   3: 8.179 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.070 ±(99.9%) 3.552 ops/ms [Average]
  (min, avg, max) = (7.846, 8.070, 8.187), stdev = 0.195
  CI (99.9%): [4.518, 11.623] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 8.249 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.688 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.533 ±(99.9%) 0.004 ms/op
Iteration   1: 3.416 ±(99.9%) 0.006 ms/op
Iteration   2: 3.356 ±(99.9%) 0.002 ms/op
Iteration   3: 3.230 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.334 ±(99.9%) 1.735 ms/op [Average]
  (min, avg, max) = (3.230, 3.334, 3.416), stdev = 0.095
  CI (99.9%): [1.599, 5.069] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 7.355 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.565 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.256 ±(99.9%) 0.007 ms/op
Iteration   1: 3.232 ±(99.9%) 0.009 ms/op
Iteration   2: 3.247 ±(99.9%) 0.003 ms/op
Iteration   3: 3.288 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.256 ±(99.9%) 0.524 ms/op [Average]
  (min, avg, max) = (3.232, 3.256, 3.288), stdev = 0.029
  CI (99.9%): [2.732, 3.779] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 9.346 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.545 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.522 ±(99.9%) 0.007 ms/op
Iteration   1: 3.425 ±(99.9%) 0.004 ms/op
Iteration   2: 3.377 ±(99.9%) 0.010 ms/op
Iteration   3: 3.411 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.404 ±(99.9%) 0.444 ms/op [Average]
  (min, avg, max) = (3.377, 3.404, 3.425), stdev = 0.024
  CI (99.9%): [2.960, 3.849] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 10.122 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 4.305 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.108 ±(99.9%) 0.006 ms/op
Iteration   1: 3.866 ±(99.9%) 0.012 ms/op
Iteration   2: 3.881 ±(99.9%) 0.011 ms/op
Iteration   3: 3.948 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.898 ±(99.9%) 0.795 ms/op [Average]
  (min, avg, max) = (3.866, 3.898, 3.948), stdev = 0.044
  CI (99.9%): [3.103, 4.693] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 8.724 ±(99.9%) 0.107 ms/op
# Warmup Iteration   2: 3.965 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.483 ±(99.9%) 0.011 ms/op
Iteration   1: 3.391 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.296 ms/op
                 createUser·p0.50:   3.285 ms/op
                 createUser·p0.90:   3.863 ms/op
                 createUser·p0.95:   4.157 ms/op
                 createUser·p0.99:   6.119 ms/op
                 createUser·p0.999:  18.892 ms/op
                 createUser·p0.9999: 22.104 ms/op
                 createUser·p1.00:   23.003 ms/op

Iteration   2: 3.553 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.687 ms/op
                 createUser·p0.50:   3.408 ms/op
                 createUser·p0.90:   4.174 ms/op
                 createUser·p0.95:   4.514 ms/op
                 createUser·p0.99:   5.947 ms/op
                 createUser·p0.999:  19.300 ms/op
                 createUser·p0.9999: 22.608 ms/op
                 createUser·p1.00:   23.560 ms/op

Iteration   3: 3.397 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.645 ms/op
                 createUser·p0.50:   3.269 ms/op
                 createUser·p0.90:   3.777 ms/op
                 createUser·p0.95:   4.166 ms/op
                 createUser·p0.99:   6.234 ms/op
                 createUser·p0.999:  19.137 ms/op
                 createUser·p0.9999: 31.987 ms/op
                 createUser·p1.00:   33.554 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 278761
  mean =      3.445 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12257 
    [ 2.500,  5.000) = 258877 
    [ 5.000,  7.500) = 6753 
    [ 7.500, 10.000) = 452 
    [10.000, 12.500) = 47 
    [12.500, 15.000) = 47 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 97 
    [20.000, 22.500) = 125 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 8 
    [30.000, 32.500) = 50 
    [32.500, 35.000) = 4 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.687 ms/op
     p(50.0000) =      3.338 ms/op
     p(90.0000) =      3.981 ms/op
     p(95.0000) =      4.293 ms/op
     p(99.0000) =      6.054 ms/op
     p(99.9000) =     19.013 ms/op
     p(99.9900) =     31.072 ms/op
     p(99.9990) =     33.306 ms/op
     p(99.9999) =     33.554 ms/op
    p(100.0000) =     33.554 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 9.099 ±(99.9%) 0.111 ms/op
# Warmup Iteration   2: 3.599 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.356 ±(99.9%) 0.007 ms/op
Iteration   1: 3.182 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.642 ms/op
                 existUser·p0.50:   3.117 ms/op
                 existUser·p0.90:   3.346 ms/op
                 existUser·p0.95:   3.641 ms/op
                 existUser·p0.99:   4.801 ms/op
                 existUser·p0.999:  10.313 ms/op
                 existUser·p0.9999: 22.570 ms/op
                 existUser·p1.00:   23.527 ms/op

Iteration   2: 3.279 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.757 ms/op
                 existUser·p0.50:   3.277 ms/op
                 existUser·p0.90:   3.437 ms/op
                 existUser·p0.95:   3.797 ms/op
                 existUser·p0.99:   5.390 ms/op
                 existUser·p0.999:  10.410 ms/op
                 existUser·p0.9999: 24.780 ms/op
                 existUser·p1.00:   26.018 ms/op

Iteration   3: 3.361 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.071 ms/op
                 existUser·p0.50:   3.215 ms/op
                 existUser·p0.90:   3.768 ms/op
                 existUser·p0.95:   4.092 ms/op
                 existUser·p0.99:   5.710 ms/op
                 existUser·p0.999:  19.226 ms/op
                 existUser·p0.9999: 25.575 ms/op
                 existUser·p1.00:   26.313 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 293298
  mean =      3.272 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12833 
    [ 2.500,  5.000) = 276179 
    [ 5.000,  7.500) = 3591 
    [ 7.500, 10.000) = 330 
    [10.000, 12.500) = 57 
    [12.500, 15.000) = 20 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 12 
    [20.000, 22.500) = 160 
    [22.500, 25.000) = 93 
    [25.000, 27.500) = 23 

  Percentiles, ms/op:
      p(0.0000) =      1.071 ms/op
     p(50.0000) =      3.211 ms/op
     p(90.0000) =      3.580 ms/op
     p(95.0000) =      3.883 ms/op
     p(99.0000) =      5.423 ms/op
     p(99.9000) =     13.362 ms/op
     p(99.9900) =     24.805 ms/op
     p(99.9990) =     26.083 ms/op
     p(99.9999) =     26.313 ms/op
    p(100.0000) =     26.313 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 8.824 ±(99.9%) 0.106 ms/op
# Warmup Iteration   2: 3.867 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.402 ±(99.9%) 0.009 ms/op
Iteration   1: 3.544 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.910 ms/op
                 getUser·p0.50:   3.383 ms/op
                 getUser·p0.90:   4.166 ms/op
                 getUser·p0.95:   4.882 ms/op
                 getUser·p0.99:   6.234 ms/op
                 getUser·p0.999:  15.417 ms/op
                 getUser·p0.9999: 23.806 ms/op
                 getUser·p1.00:   24.478 ms/op

Iteration   2: 3.483 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.346 ms/op
                 getUser·p0.50:   3.355 ms/op
                 getUser·p0.90:   4.055 ms/op
                 getUser·p0.95:   4.407 ms/op
                 getUser·p0.99:   5.587 ms/op
                 getUser·p0.999:  21.037 ms/op
                 getUser·p0.9999: 29.856 ms/op
                 getUser·p1.00:   31.752 ms/op

Iteration   3: 3.418 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.008 ms/op
                 getUser·p0.50:   3.326 ms/op
                 getUser·p0.90:   3.695 ms/op
                 getUser·p0.95:   3.871 ms/op
                 getUser·p0.99:   6.259 ms/op
                 getUser·p0.999:  19.986 ms/op
                 getUser·p0.9999: 31.554 ms/op
                 getUser·p1.00:   32.801 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 275526
  mean =      3.481 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11225 
    [ 2.500,  5.000) = 256045 
    [ 5.000,  7.500) = 7012 
    [ 7.500, 10.000) = 821 
    [10.000, 12.500) = 83 
    [12.500, 15.000) = 46 
    [15.000, 17.500) = 37 
    [17.500, 20.000) = 22 
    [20.000, 22.500) = 83 
    [22.500, 25.000) = 56 
    [25.000, 27.500) = 14 
    [27.500, 30.000) = 45 
    [30.000, 32.500) = 33 
    [32.500, 35.000) = 4 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.910 ms/op
     p(50.0000) =      3.359 ms/op
     p(90.0000) =      3.977 ms/op
     p(95.0000) =      4.383 ms/op
     p(99.0000) =      6.062 ms/op
     p(99.9000) =     15.417 ms/op
     p(99.9900) =     30.686 ms/op
     p(99.9990) =     32.678 ms/op
     p(99.9999) =     32.801 ms/op
    p(100.0000) =     32.801 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 10.941 ±(99.9%) 0.136 ms/op
# Warmup Iteration   2: 4.510 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.178 ±(99.9%) 0.013 ms/op
Iteration   1: 4.005 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   2.154 ms/op
                 listUser·p0.50:   3.916 ms/op
                 listUser·p0.90:   4.112 ms/op
                 listUser·p0.95:   4.645 ms/op
                 listUser·p0.99:   7.258 ms/op
                 listUser·p0.999:  21.827 ms/op
                 listUser·p0.9999: 33.948 ms/op
                 listUser·p1.00:   34.013 ms/op

Iteration   2: 3.985 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.466 ms/op
                 listUser·p0.50:   3.879 ms/op
                 listUser·p0.90:   4.571 ms/op
                 listUser·p0.95:   4.858 ms/op
                 listUser·p0.99:   6.701 ms/op
                 listUser·p0.999:  14.402 ms/op
                 listUser·p0.9999: 16.724 ms/op
                 listUser·p1.00:   17.990 ms/op

Iteration   3: 3.927 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.997 ms/op
                 listUser·p0.50:   3.822 ms/op
                 listUser·p0.90:   4.276 ms/op
                 listUser·p0.95:   4.489 ms/op
                 listUser·p0.99:   7.594 ms/op
                 listUser·p0.999:  14.352 ms/op
                 listUser·p0.9999: 22.479 ms/op
                 listUser·p1.00:   22.577 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 241636
  mean =      3.972 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24 
    [ 2.500,  5.000) = 233677 
    [ 5.000,  7.500) = 5849 
    [ 7.500, 10.000) = 1309 
    [10.000, 12.500) = 249 
    [12.500, 15.000) = 223 
    [15.000, 17.500) = 162 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 34 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 6 
    [27.500, 30.000) = 23 
    [30.000, 32.500) = 10 
    [32.500, 35.000) = 27 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.997 ms/op
     p(50.0000) =      3.875 ms/op
     p(90.0000) =      4.309 ms/op
     p(95.0000) =      4.719 ms/op
     p(99.0000) =      7.140 ms/op
     p(99.9000) =     15.401 ms/op
     p(99.9900) =     32.506 ms/op
     p(99.9990) =     33.986 ms/op
     p(99.9999) =     34.013 ms/op
    p(100.0000) =     34.013 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.459 ± 3.529  ops/ms
ClientPb.existUser                       thrpt       3   9.633 ± 1.665  ops/ms
ClientPb.getUser                         thrpt       3   9.597 ± 3.159  ops/ms
ClientPb.listUser                        thrpt       3   8.070 ± 3.552  ops/ms
ClientPb.createUser                       avgt       3   3.334 ± 1.735   ms/op
ClientPb.existUser                        avgt       3   3.256 ± 0.524   ms/op
ClientPb.getUser                          avgt       3   3.404 ± 0.444   ms/op
ClientPb.listUser                         avgt       3   3.898 ± 0.795   ms/op
ClientPb.createUser                     sample  278761   3.445 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.687           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.338           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.981           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.293           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.054           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.013           ms/op
ClientPb.createUser:createUser·p0.9999  sample          31.072           ms/op
ClientPb.createUser:createUser·p1.00    sample          33.554           ms/op
ClientPb.existUser                      sample  293298   3.272 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.071           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.211           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.580           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.883           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.423           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.362           ms/op
ClientPb.existUser:existUser·p0.9999    sample          24.805           ms/op
ClientPb.existUser:existUser·p1.00      sample          26.313           ms/op
ClientPb.getUser                        sample  275526   3.481 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.910           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.359           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.977           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.383           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.062           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.417           ms/op
ClientPb.getUser:getUser·p0.9999        sample          30.686           ms/op
ClientPb.getUser:getUser·p1.00          sample          32.801           ms/op
ClientPb.listUser                       sample  241636   3.972 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.997           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.875           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.309           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.719           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.140           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.401           ms/op
ClientPb.listUser:listUser·p0.9999      sample          32.506           ms/op
ClientPb.listUser:listUser·p1.00        sample          34.013           ms/op
