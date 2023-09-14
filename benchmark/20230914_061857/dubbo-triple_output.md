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
# Warmup Iteration   1: 2.093 ops/ms
# Warmup Iteration   2: 5.473 ops/ms
# Warmup Iteration   3: 8.280 ops/ms
Iteration   1: 8.874 ops/ms
Iteration   2: 9.190 ops/ms
Iteration   3: 9.115 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.060 ±(99.9%) 3.015 ops/ms [Average]
  (min, avg, max) = (8.874, 9.060, 9.190), stdev = 0.165
  CI (99.9%): [6.045, 12.075] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 2.928 ops/ms
# Warmup Iteration   2: 8.526 ops/ms
# Warmup Iteration   3: 9.006 ops/ms
Iteration   1: 9.355 ops/ms
Iteration   2: 9.609 ops/ms
Iteration   3: 9.590 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.518 ±(99.9%) 2.583 ops/ms [Average]
  (min, avg, max) = (9.355, 9.518, 9.609), stdev = 0.142
  CI (99.9%): [6.935, 12.101] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.119 ops/ms
# Warmup Iteration   2: 8.313 ops/ms
# Warmup Iteration   3: 8.960 ops/ms
Iteration   1: 8.998 ops/ms
Iteration   2: 9.255 ops/ms
Iteration   3: 9.136 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.130 ±(99.9%) 2.339 ops/ms [Average]
  (min, avg, max) = (8.998, 9.130, 9.255), stdev = 0.128
  CI (99.9%): [6.791, 11.469] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.269 ops/ms
# Warmup Iteration   2: 7.264 ops/ms
# Warmup Iteration   3: 7.725 ops/ms
Iteration   1: 7.790 ops/ms
Iteration   2: 8.031 ops/ms
Iteration   3: 7.956 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.925 ±(99.9%) 2.245 ops/ms [Average]
  (min, avg, max) = (7.790, 7.925, 8.031), stdev = 0.123
  CI (99.9%): [5.680, 10.170] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:43
# Fork: 1 of 1
# Warmup Iteration   1: 8.742 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.819 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.722 ±(99.9%) 0.006 ms/op
Iteration   1: 3.596 ±(99.9%) 0.008 ms/op
Iteration   2: 3.376 ±(99.9%) 0.006 ms/op
Iteration   3: 3.570 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.514 ±(99.9%) 2.193 ms/op [Average]
  (min, avg, max) = (3.376, 3.514, 3.596), stdev = 0.120
  CI (99.9%): [1.321, 5.707] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 8.728 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.454 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.389 ±(99.9%) 0.003 ms/op
Iteration   1: 3.271 ±(99.9%) 0.004 ms/op
Iteration   2: 3.337 ±(99.9%) 0.009 ms/op
Iteration   3: 3.294 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.301 ±(99.9%) 0.615 ms/op [Average]
  (min, avg, max) = (3.271, 3.301, 3.337), stdev = 0.034
  CI (99.9%): [2.686, 3.915] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 9.350 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.941 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.726 ±(99.9%) 0.005 ms/op
Iteration   1: 3.684 ±(99.9%) 0.004 ms/op
Iteration   2: 3.510 ±(99.9%) 0.007 ms/op
Iteration   3: 3.514 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.569 ±(99.9%) 1.811 ms/op [Average]
  (min, avg, max) = (3.510, 3.569, 3.684), stdev = 0.099
  CI (99.9%): [1.758, 5.380] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 10.506 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 4.631 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.199 ±(99.9%) 0.005 ms/op
Iteration   1: 4.073 ±(99.9%) 0.009 ms/op
Iteration   2: 3.987 ±(99.9%) 0.011 ms/op
Iteration   3: 4.019 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.026 ±(99.9%) 0.794 ms/op [Average]
  (min, avg, max) = (3.987, 4.026, 4.073), stdev = 0.044
  CI (99.9%): [3.232, 4.821] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 9.049 ±(99.9%) 0.125 ms/op
# Warmup Iteration   2: 3.803 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.558 ±(99.9%) 0.012 ms/op
Iteration   1: 3.453 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.614 ms/op
                 createUser·p0.50:   3.351 ms/op
                 createUser·p0.90:   3.936 ms/op
                 createUser·p0.95:   4.276 ms/op
                 createUser·p0.99:   6.791 ms/op
                 createUser·p0.999:  20.983 ms/op
                 createUser·p0.9999: 24.895 ms/op
                 createUser·p1.00:   25.756 ms/op

Iteration   2: 3.556 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.423 ms/op
                 createUser·p0.50:   3.379 ms/op
                 createUser·p0.90:   4.260 ms/op
                 createUser·p0.95:   4.522 ms/op
                 createUser·p0.99:   6.185 ms/op
                 createUser·p0.999:  22.280 ms/op
                 createUser·p0.9999: 26.083 ms/op
                 createUser·p1.00:   26.542 ms/op

Iteration   3: 3.487 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.305 ms/op
                 createUser·p0.50:   3.346 ms/op
                 createUser·p0.90:   3.899 ms/op
                 createUser·p0.95:   4.252 ms/op
                 createUser·p0.99:   6.841 ms/op
                 createUser·p0.999:  18.288 ms/op
                 createUser·p0.9999: 29.413 ms/op
                 createUser·p1.00:   30.310 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 274612
  mean =      3.498 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13094 
    [ 2.500,  5.000) = 253542 
    [ 5.000,  7.500) = 6337 
    [ 7.500, 10.000) = 904 
    [10.000, 12.500) = 342 
    [12.500, 15.000) = 73 
    [15.000, 17.500) = 12 
    [17.500, 20.000) = 39 
    [20.000, 22.500) = 55 
    [22.500, 25.000) = 121 
    [25.000, 27.500) = 60 
    [27.500, 30.000) = 29 
    [30.000, 32.500) = 4 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.305 ms/op
     p(50.0000) =      3.359 ms/op
     p(90.0000) =      4.063 ms/op
     p(95.0000) =      4.407 ms/op
     p(99.0000) =      6.627 ms/op
     p(99.9000) =     18.579 ms/op
     p(99.9900) =     27.921 ms/op
     p(99.9990) =     30.032 ms/op
     p(99.9999) =     30.310 ms/op
    p(100.0000) =     30.310 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 8.768 ±(99.9%) 0.127 ms/op
# Warmup Iteration   2: 3.662 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.382 ±(99.9%) 0.010 ms/op
Iteration   1: 3.281 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.165 ms/op
                 existUser·p0.50:   3.207 ms/op
                 existUser·p0.90:   3.600 ms/op
                 existUser·p0.95:   3.965 ms/op
                 existUser·p0.99:   6.111 ms/op
                 existUser·p0.999:  12.303 ms/op
                 existUser·p0.9999: 30.376 ms/op
                 existUser·p1.00:   31.982 ms/op

Iteration   2: 3.328 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.208 ms/op
                 existUser·p0.50:   3.203 ms/op
                 existUser·p0.90:   3.670 ms/op
                 existUser·p0.95:   4.358 ms/op
                 existUser·p0.99:   6.013 ms/op
                 existUser·p0.999:  21.607 ms/op
                 existUser·p0.9999: 31.130 ms/op
                 existUser·p1.00:   31.982 ms/op

Iteration   3: 3.316 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.432 ms/op
                 existUser·p0.50:   3.146 ms/op
                 existUser·p0.90:   3.645 ms/op
                 existUser·p0.95:   4.063 ms/op
                 existUser·p0.99:   6.406 ms/op
                 existUser·p0.999:  16.628 ms/op
                 existUser·p0.9999: 29.503 ms/op
                 existUser·p1.00:   30.179 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 290033
  mean =      3.309 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12000 
    [ 2.500,  5.000) = 271420 
    [ 5.000,  7.500) = 5094 
    [ 7.500, 10.000) = 985 
    [10.000, 12.500) = 198 
    [12.500, 15.000) = 48 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 12 
    [20.000, 22.500) = 52 
    [22.500, 25.000) = 64 
    [25.000, 27.500) = 43 
    [27.500, 30.000) = 76 
    [30.000, 32.500) = 41 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.165 ms/op
     p(50.0000) =      3.191 ms/op
     p(90.0000) =      3.641 ms/op
     p(95.0000) =      4.100 ms/op
     p(99.0000) =      6.234 ms/op
     p(99.9000) =     14.451 ms/op
     p(99.9900) =     30.179 ms/op
     p(99.9990) =     31.952 ms/op
     p(99.9999) =     31.982 ms/op
    p(100.0000) =     31.982 ms/op


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
# Warmup Iteration   1: 8.561 ±(99.9%) 0.126 ms/op
# Warmup Iteration   2: 3.793 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.512 ±(99.9%) 0.011 ms/op
Iteration   1: 3.587 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.208 ms/op
                 getUser·p0.50:   3.404 ms/op
                 getUser·p0.90:   4.219 ms/op
                 getUser·p0.95:   5.276 ms/op
                 getUser·p0.99:   6.947 ms/op
                 getUser·p0.999:  21.823 ms/op
                 getUser·p0.9999: 24.740 ms/op
                 getUser·p1.00:   25.887 ms/op

Iteration   2: 3.492 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.231 ms/op
                 getUser·p0.50:   3.404 ms/op
                 getUser·p0.90:   3.990 ms/op
                 getUser·p0.95:   4.284 ms/op
                 getUser·p0.99:   6.099 ms/op
                 getUser·p0.999:  10.715 ms/op
                 getUser·p0.9999: 30.557 ms/op
                 getUser·p1.00:   30.933 ms/op

Iteration   3: 3.428 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.811 ms/op
                 getUser·p0.50:   3.318 ms/op
                 getUser·p0.90:   3.801 ms/op
                 getUser·p0.95:   4.092 ms/op
                 getUser·p0.99:   6.304 ms/op
                 getUser·p0.999:  21.398 ms/op
                 getUser·p0.9999: 31.151 ms/op
                 getUser·p1.00:   31.752 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 274164
  mean =      3.501 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10820 
    [ 2.500,  5.000) = 253582 
    [ 5.000,  7.500) = 8020 
    [ 7.500, 10.000) = 1211 
    [10.000, 12.500) = 218 
    [12.500, 15.000) = 47 
    [15.000, 17.500) = 10 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 44 
    [22.500, 25.000) = 110 
    [25.000, 27.500) = 38 
    [27.500, 30.000) = 25 
    [30.000, 32.500) = 39 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.811 ms/op
     p(50.0000) =      3.383 ms/op
     p(90.0000) =      3.973 ms/op
     p(95.0000) =      4.456 ms/op
     p(99.0000) =      6.562 ms/op
     p(99.9000) =     13.888 ms/op
     p(99.9900) =     30.409 ms/op
     p(99.9990) =     31.622 ms/op
     p(99.9999) =     31.752 ms/op
    p(100.0000) =     31.752 ms/op


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
# Warmup Iteration   1: 11.661 ±(99.9%) 0.174 ms/op
# Warmup Iteration   2: 4.536 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.163 ±(99.9%) 0.015 ms/op
Iteration   1: 4.107 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.923 ms/op
                 listUser·p0.50:   3.895 ms/op
                 listUser·p0.90:   4.383 ms/op
                 listUser·p0.95:   4.907 ms/op
                 listUser·p0.99:   8.471 ms/op
                 listUser·p0.999:  24.216 ms/op
                 listUser·p0.9999: 26.753 ms/op
                 listUser·p1.00:   27.066 ms/op

Iteration   2: 3.962 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.009 ms/op
                 listUser·p0.50:   3.883 ms/op
                 listUser·p0.90:   4.268 ms/op
                 listUser·p0.95:   4.555 ms/op
                 listUser·p0.99:   7.127 ms/op
                 listUser·p0.999:  16.127 ms/op
                 listUser·p0.9999: 19.167 ms/op
                 listUser·p1.00:   20.283 ms/op

Iteration   3: 3.969 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.294 ms/op
                 listUser·p0.50:   3.903 ms/op
                 listUser·p0.90:   4.088 ms/op
                 listUser·p0.95:   4.563 ms/op
                 listUser·p0.99:   7.217 ms/op
                 listUser·p0.999:  16.335 ms/op
                 listUser·p0.9999: 17.564 ms/op
                 listUser·p1.00:   17.826 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 239122
  mean =      4.011 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 32 
    [ 2.500,  5.000) = 230411 
    [ 5.000,  7.500) = 6046 
    [ 7.500, 10.000) = 1558 
    [10.000, 12.500) = 512 
    [12.500, 15.000) = 75 
    [15.000, 17.500) = 305 
    [17.500, 20.000) = 54 
    [20.000, 22.500) = 16 
    [22.500, 25.000) = 72 
    [25.000, 27.500) = 41 

  Percentiles, ms/op:
      p(0.0000) =      1.923 ms/op
     p(50.0000) =      3.895 ms/op
     p(90.0000) =      4.293 ms/op
     p(95.0000) =      4.637 ms/op
     p(99.0000) =      7.692 ms/op
     p(99.9000) =     16.839 ms/op
     p(99.9900) =     25.365 ms/op
     p(99.9990) =     26.935 ms/op
     p(99.9999) =     27.066 ms/op
    p(100.0000) =     27.066 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.060 ± 3.015  ops/ms
ClientPb.existUser                       thrpt       3   9.518 ± 2.583  ops/ms
ClientPb.getUser                         thrpt       3   9.130 ± 2.339  ops/ms
ClientPb.listUser                        thrpt       3   7.925 ± 2.245  ops/ms
ClientPb.createUser                       avgt       3   3.514 ± 2.193   ms/op
ClientPb.existUser                        avgt       3   3.301 ± 0.615   ms/op
ClientPb.getUser                          avgt       3   3.569 ± 1.811   ms/op
ClientPb.listUser                         avgt       3   4.026 ± 0.794   ms/op
ClientPb.createUser                     sample  274612   3.498 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.305           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.359           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.063           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.407           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.627           ms/op
ClientPb.createUser:createUser·p0.999   sample          18.579           ms/op
ClientPb.createUser:createUser·p0.9999  sample          27.921           ms/op
ClientPb.createUser:createUser·p1.00    sample          30.310           ms/op
ClientPb.existUser                      sample  290033   3.309 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.165           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.191           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.641           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.100           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.234           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.451           ms/op
ClientPb.existUser:existUser·p0.9999    sample          30.179           ms/op
ClientPb.existUser:existUser·p1.00      sample          31.982           ms/op
ClientPb.getUser                        sample  274164   3.501 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.811           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.383           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.973           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.456           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.562           ms/op
ClientPb.getUser:getUser·p0.999         sample          13.888           ms/op
ClientPb.getUser:getUser·p0.9999        sample          30.409           ms/op
ClientPb.getUser:getUser·p1.00          sample          31.752           ms/op
ClientPb.listUser                       sample  239122   4.011 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.923           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.895           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.293           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.637           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.692           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.839           ms/op
ClientPb.listUser:listUser·p0.9999      sample          25.365           ms/op
ClientPb.listUser:listUser·p1.00        sample          27.066           ms/op
