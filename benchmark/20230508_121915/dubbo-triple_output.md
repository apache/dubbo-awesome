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
# Warmup Iteration   1: 2.543 ops/ms
# Warmup Iteration   2: 5.873 ops/ms
# Warmup Iteration   3: 9.135 ops/ms
Iteration   1: 9.662 ops/ms
Iteration   2: 9.939 ops/ms
Iteration   3: 10.089 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.897 ±(99.9%) 3.954 ops/ms [Average]
  (min, avg, max) = (9.662, 9.897, 10.089), stdev = 0.217
  CI (99.9%): [5.943, 13.850] (assumes normal distribution)


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
# Warmup Iteration   1: 3.997 ops/ms
# Warmup Iteration   2: 9.640 ops/ms
# Warmup Iteration   3: 10.304 ops/ms
Iteration   1: 10.676 ops/ms
Iteration   2: 10.393 ops/ms
Iteration   3: 10.219 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.429 ±(99.9%) 4.208 ops/ms [Average]
  (min, avg, max) = (10.219, 10.429, 10.676), stdev = 0.231
  CI (99.9%): [6.221, 14.637] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.559 ops/ms
# Warmup Iteration   2: 9.547 ops/ms
# Warmup Iteration   3: 9.532 ops/ms
Iteration   1: 10.121 ops/ms
Iteration   2: 10.053 ops/ms
Iteration   3: 10.264 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.146 ±(99.9%) 1.965 ops/ms [Average]
  (min, avg, max) = (10.053, 10.146, 10.264), stdev = 0.108
  CI (99.9%): [8.181, 12.112] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 3.643 ops/ms
# Warmup Iteration   2: 7.805 ops/ms
# Warmup Iteration   3: 8.462 ops/ms
Iteration   1: 8.730 ops/ms
Iteration   2: 8.715 ops/ms
Iteration   3: 8.395 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.613 ±(99.9%) 3.448 ops/ms [Average]
  (min, avg, max) = (8.395, 8.613, 8.730), stdev = 0.189
  CI (99.9%): [5.166, 12.061] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 7.884 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.527 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.225 ±(99.9%) 0.007 ms/op
Iteration   1: 3.436 ±(99.9%) 0.008 ms/op
Iteration   2: 3.302 ±(99.9%) 0.003 ms/op
Iteration   3: 3.105 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.281 ±(99.9%) 3.035 ms/op [Average]
  (min, avg, max) = (3.105, 3.281, 3.436), stdev = 0.166
  CI (99.9%): [0.246, 6.316] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 7.318 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.365 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.287 ±(99.9%) 0.003 ms/op
Iteration   1: 3.259 ±(99.9%) 0.006 ms/op
Iteration   2: 3.025 ±(99.9%) 0.002 ms/op
Iteration   3: 3.003 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.096 ±(99.9%) 2.583 ms/op [Average]
  (min, avg, max) = (3.003, 3.096, 3.259), stdev = 0.142
  CI (99.9%): [0.513, 5.679] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 7.795 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.361 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.177 ±(99.9%) 0.003 ms/op
Iteration   1: 3.208 ±(99.9%) 0.005 ms/op
Iteration   2: 3.183 ±(99.9%) 0.002 ms/op
Iteration   3: 3.269 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.220 ±(99.9%) 0.810 ms/op [Average]
  (min, avg, max) = (3.183, 3.220, 3.269), stdev = 0.044
  CI (99.9%): [2.411, 4.030] (assumes normal distribution)


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
# Warmup Iteration   1: 8.706 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 4.007 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.766 ±(99.9%) 0.005 ms/op
Iteration   1: 3.800 ±(99.9%) 0.005 ms/op
Iteration   2: 3.807 ±(99.9%) 0.007 ms/op
Iteration   3: 3.628 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.745 ±(99.9%) 1.851 ms/op [Average]
  (min, avg, max) = (3.628, 3.745, 3.807), stdev = 0.101
  CI (99.9%): [1.894, 5.596] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 7.990 ±(99.9%) 0.091 ms/op
# Warmup Iteration   2: 3.631 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.271 ±(99.9%) 0.009 ms/op
Iteration   1: 3.231 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.327 ms/op
                 createUser·p0.50:   3.146 ms/op
                 createUser·p0.90:   3.658 ms/op
                 createUser·p0.95:   4.026 ms/op
                 createUser·p0.99:   6.234 ms/op
                 createUser·p0.999:  18.707 ms/op
                 createUser·p0.9999: 20.254 ms/op
                 createUser·p1.00:   20.513 ms/op

Iteration   2: 3.256 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.083 ms/op
                 createUser·p0.50:   3.142 ms/op
                 createUser·p0.90:   3.756 ms/op
                 createUser·p0.95:   3.998 ms/op
                 createUser·p0.99:   5.669 ms/op
                 createUser·p0.999:  18.341 ms/op
                 createUser·p0.9999: 22.381 ms/op
                 createUser·p1.00:   22.741 ms/op

Iteration   3: 3.184 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.579 ms/op
                 createUser·p0.50:   3.060 ms/op
                 createUser·p0.90:   3.584 ms/op
                 createUser·p0.95:   3.903 ms/op
                 createUser·p0.99:   5.710 ms/op
                 createUser·p0.999:  15.286 ms/op
                 createUser·p0.9999: 20.772 ms/op
                 createUser·p1.00:   21.922 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 297799
  mean =      3.223 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15533 
    [ 2.500,  5.000) = 276078 
    [ 5.000,  7.500) = 5150 
    [ 7.500, 10.000) = 515 
    [10.000, 12.500) = 114 
    [12.500, 15.000) = 16 
    [15.000, 17.500) = 111 
    [17.500, 20.000) = 159 
    [20.000, 22.500) = 117 
    [22.500, 25.000) = 6 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.083 ms/op
     p(50.0000) =      3.121 ms/op
     p(90.0000) =      3.682 ms/op
     p(95.0000) =      3.985 ms/op
     p(99.0000) =      5.808 ms/op
     p(99.9000) =     17.334 ms/op
     p(99.9900) =     21.896 ms/op
     p(99.9990) =     22.644 ms/op
     p(99.9999) =     22.741 ms/op
    p(100.0000) =     22.741 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 6.854 ±(99.9%) 0.079 ms/op
# Warmup Iteration   2: 3.456 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.263 ±(99.9%) 0.009 ms/op
Iteration   1: 3.040 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.065 ms/op
                 existUser·p0.50:   2.941 ms/op
                 existUser·p0.90:   3.310 ms/op
                 existUser·p0.95:   3.486 ms/op
                 existUser·p0.99:   5.259 ms/op
                 existUser·p0.999:  13.625 ms/op
                 existUser·p0.9999: 20.480 ms/op
                 existUser·p1.00:   21.266 ms/op

Iteration   2: 3.029 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.300 ms/op
                 existUser·p0.50:   2.945 ms/op
                 existUser·p0.90:   3.281 ms/op
                 existUser·p0.95:   3.441 ms/op
                 existUser·p0.99:   5.169 ms/op
                 existUser·p0.999:  11.682 ms/op
                 existUser·p0.9999: 26.459 ms/op
                 existUser·p1.00:   27.197 ms/op

Iteration   3: 3.150 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.343 ms/op
                 existUser·p0.50:   3.006 ms/op
                 existUser·p0.90:   3.662 ms/op
                 existUser·p0.95:   4.194 ms/op
                 existUser·p0.99:   5.325 ms/op
                 existUser·p0.999:  13.875 ms/op
                 existUser·p0.9999: 22.539 ms/op
                 existUser·p1.00:   23.495 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 312319
  mean =      3.072 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10752 
    [ 2.500,  5.000) = 297434 
    [ 5.000,  7.500) = 3243 
    [ 7.500, 10.000) = 367 
    [10.000, 12.500) = 159 
    [12.500, 15.000) = 88 
    [15.000, 17.500) = 20 
    [17.500, 20.000) = 93 
    [20.000, 22.500) = 101 
    [22.500, 25.000) = 38 
    [25.000, 27.500) = 24 

  Percentiles, ms/op:
      p(0.0000) =      1.065 ms/op
     p(50.0000) =      2.961 ms/op
     p(90.0000) =      3.342 ms/op
     p(95.0000) =      3.715 ms/op
     p(99.0000) =      5.259 ms/op
     p(99.9000) =     13.058 ms/op
     p(99.9900) =     24.659 ms/op
     p(99.9990) =     26.866 ms/op
     p(99.9999) =     27.197 ms/op
    p(100.0000) =     27.197 ms/op


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
# Warmup Iteration   1: 7.397 ±(99.9%) 0.099 ms/op
# Warmup Iteration   2: 3.448 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.337 ±(99.9%) 0.009 ms/op
Iteration   1: 3.398 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.844 ms/op
                 getUser·p0.50:   3.244 ms/op
                 getUser·p0.90:   4.084 ms/op
                 getUser·p0.95:   4.653 ms/op
                 getUser·p0.99:   6.283 ms/op
                 getUser·p0.999:  18.534 ms/op
                 getUser·p0.9999: 25.963 ms/op
                 getUser·p1.00:   26.509 ms/op

Iteration   2: 3.289 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.425 ms/op
                 getUser·p0.50:   3.215 ms/op
                 getUser·p0.90:   3.764 ms/op
                 getUser·p0.95:   4.121 ms/op
                 getUser·p0.99:   5.603 ms/op
                 getUser·p0.999:  12.234 ms/op
                 getUser·p0.9999: 22.553 ms/op
                 getUser·p1.00:   23.265 ms/op

Iteration   3: 3.422 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.354 ms/op
                 getUser·p0.50:   3.269 ms/op
                 getUser·p0.90:   3.961 ms/op
                 getUser·p0.95:   4.694 ms/op
                 getUser·p0.99:   6.169 ms/op
                 getUser·p0.999:  14.868 ms/op
                 getUser·p0.9999: 22.041 ms/op
                 getUser·p1.00:   22.544 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 285103
  mean =      3.369 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21886 
    [ 2.500,  5.000) = 253516 
    [ 5.000,  7.500) = 8809 
    [ 7.500, 10.000) = 479 
    [10.000, 12.500) = 109 
    [12.500, 15.000) = 12 
    [15.000, 17.500) = 56 
    [17.500, 20.000) = 58 
    [20.000, 22.500) = 132 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 31 

  Percentiles, ms/op:
      p(0.0000) =      0.844 ms/op
     p(50.0000) =      3.240 ms/op
     p(90.0000) =      3.932 ms/op
     p(95.0000) =      4.383 ms/op
     p(99.0000) =      5.931 ms/op
     p(99.9000) =     15.366 ms/op
     p(99.9900) =     25.084 ms/op
     p(99.9990) =     26.411 ms/op
     p(99.9999) =     26.509 ms/op
    p(100.0000) =     26.509 ms/op


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
# Warmup Iteration   1: 8.880 ±(99.9%) 0.112 ms/op
# Warmup Iteration   2: 4.218 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.844 ±(99.9%) 0.012 ms/op
Iteration   1: 3.708 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.513 ms/op
                 listUser·p0.50:   3.551 ms/op
                 listUser·p0.90:   4.030 ms/op
                 listUser·p0.95:   4.350 ms/op
                 listUser·p0.99:   7.062 ms/op
                 listUser·p0.999:  13.972 ms/op
                 listUser·p0.9999: 26.579 ms/op
                 listUser·p1.00:   27.034 ms/op

Iteration   2: 3.637 ±(99.9%) 0.007 ms/op
                 listUser·p0.00:   2.183 ms/op
                 listUser·p0.50:   3.539 ms/op
                 listUser·p0.90:   3.932 ms/op
                 listUser·p0.95:   4.096 ms/op
                 listUser·p0.99:   6.365 ms/op
                 listUser·p0.999:  12.698 ms/op
                 listUser·p0.9999: 15.934 ms/op
                 listUser·p1.00:   19.333 ms/op

Iteration   3: 3.694 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.269 ms/op
                 listUser·p0.50:   3.584 ms/op
                 listUser·p0.90:   3.969 ms/op
                 listUser·p0.95:   4.166 ms/op
                 listUser·p0.99:   6.668 ms/op
                 listUser·p0.999:  13.526 ms/op
                 listUser·p0.9999: 21.299 ms/op
                 listUser·p1.00:   21.430 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 260580
  mean =      3.680 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 61 
    [ 2.500,  5.000) = 253789 
    [ 5.000,  7.500) = 5039 
    [ 7.500, 10.000) = 1109 
    [10.000, 12.500) = 193 
    [12.500, 15.000) = 258 
    [15.000, 17.500) = 51 
    [17.500, 20.000) = 38 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 21 

  Percentiles, ms/op:
      p(0.0000) =      1.513 ms/op
     p(50.0000) =      3.555 ms/op
     p(90.0000) =      3.977 ms/op
     p(95.0000) =      4.182 ms/op
     p(99.0000) =      6.767 ms/op
     p(99.9000) =     13.311 ms/op
     p(99.9900) =     24.607 ms/op
     p(99.9990) =     26.856 ms/op
     p(99.9999) =     27.034 ms/op
    p(100.0000) =     27.034 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.897 ± 3.954  ops/ms
ClientPb.existUser                       thrpt       3  10.429 ± 4.208  ops/ms
ClientPb.getUser                         thrpt       3  10.146 ± 1.965  ops/ms
ClientPb.listUser                        thrpt       3   8.613 ± 3.448  ops/ms
ClientPb.createUser                       avgt       3   3.281 ± 3.035   ms/op
ClientPb.existUser                        avgt       3   3.096 ± 2.583   ms/op
ClientPb.getUser                          avgt       3   3.220 ± 0.810   ms/op
ClientPb.listUser                         avgt       3   3.745 ± 1.851   ms/op
ClientPb.createUser                     sample  297799   3.223 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.083           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.121           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.682           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.985           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.808           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.334           ms/op
ClientPb.createUser:createUser·p0.9999  sample          21.896           ms/op
ClientPb.createUser:createUser·p1.00    sample          22.741           ms/op
ClientPb.existUser                      sample  312319   3.072 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.065           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.961           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.342           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.715           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.259           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.058           ms/op
ClientPb.existUser:existUser·p0.9999    sample          24.659           ms/op
ClientPb.existUser:existUser·p1.00      sample          27.197           ms/op
ClientPb.getUser                        sample  285103   3.369 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.844           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.240           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.932           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.383           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.931           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.366           ms/op
ClientPb.getUser:getUser·p0.9999        sample          25.084           ms/op
ClientPb.getUser:getUser·p1.00          sample          26.509           ms/op
ClientPb.listUser                       sample  260580   3.680 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.513           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.555           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.977           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.182           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.767           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.311           ms/op
ClientPb.listUser:listUser·p0.9999      sample          24.607           ms/op
ClientPb.listUser:listUser·p1.00        sample          27.034           ms/op
