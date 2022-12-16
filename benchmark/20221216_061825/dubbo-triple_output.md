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
# Warmup Iteration   1: 2.052 ops/ms
# Warmup Iteration   2: 5.453 ops/ms
# Warmup Iteration   3: 8.490 ops/ms
Iteration   1: 9.373 ops/ms
Iteration   2: 8.981 ops/ms
Iteration   3: 9.455 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.269 ±(99.9%) 4.623 ops/ms [Average]
  (min, avg, max) = (8.981, 9.269, 9.455), stdev = 0.253
  CI (99.9%): [4.646, 13.893] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 3.421 ops/ms
# Warmup Iteration   2: 9.359 ops/ms
# Warmup Iteration   3: 9.382 ops/ms
Iteration   1: 9.740 ops/ms
Iteration   2: 10.057 ops/ms
Iteration   3: 9.894 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.897 ±(99.9%) 2.893 ops/ms [Average]
  (min, avg, max) = (9.740, 9.897, 10.057), stdev = 0.159
  CI (99.9%): [7.004, 12.790] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.076 ops/ms
# Warmup Iteration   2: 8.729 ops/ms
# Warmup Iteration   3: 9.161 ops/ms
Iteration   1: 9.230 ops/ms
Iteration   2: 9.459 ops/ms
Iteration   3: 9.326 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.338 ±(99.9%) 2.100 ops/ms [Average]
  (min, avg, max) = (9.230, 9.338, 9.459), stdev = 0.115
  CI (99.9%): [7.238, 11.438] (assumes normal distribution)


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
# Warmup Iteration   1: 2.670 ops/ms
# Warmup Iteration   2: 7.207 ops/ms
# Warmup Iteration   3: 7.880 ops/ms
Iteration   1: 8.062 ops/ms
Iteration   2: 8.217 ops/ms
Iteration   3: 7.791 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.023 ±(99.9%) 3.933 ops/ms [Average]
  (min, avg, max) = (7.791, 8.023, 8.217), stdev = 0.216
  CI (99.9%): [4.090, 11.956] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 9.021 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 3.820 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.641 ±(99.9%) 0.006 ms/op
Iteration   1: 3.470 ±(99.9%) 0.004 ms/op
Iteration   2: 3.377 ±(99.9%) 0.006 ms/op
Iteration   3: 3.347 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.398 ±(99.9%) 1.164 ms/op [Average]
  (min, avg, max) = (3.347, 3.398, 3.470), stdev = 0.064
  CI (99.9%): [2.234, 4.562] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 8.731 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 4.146 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.345 ±(99.9%) 0.004 ms/op
Iteration   1: 3.355 ±(99.9%) 0.007 ms/op
Iteration   2: 3.257 ±(99.9%) 0.010 ms/op
Iteration   3: 3.402 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.338 ±(99.9%) 1.348 ms/op [Average]
  (min, avg, max) = (3.257, 3.338, 3.402), stdev = 0.074
  CI (99.9%): [1.990, 4.686] (assumes normal distribution)


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
# Warmup Iteration   1: 9.914 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.537 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.451 ±(99.9%) 0.005 ms/op
Iteration   1: 3.478 ±(99.9%) 0.005 ms/op
Iteration   2: 3.404 ±(99.9%) 0.010 ms/op
Iteration   3: 3.270 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.384 ±(99.9%) 1.927 ms/op [Average]
  (min, avg, max) = (3.270, 3.384, 3.478), stdev = 0.106
  CI (99.9%): [1.457, 5.311] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 11.194 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 4.415 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 4.026 ±(99.9%) 0.010 ms/op
Iteration   1: 3.982 ±(99.9%) 0.008 ms/op
Iteration   2: 4.028 ±(99.9%) 0.009 ms/op
Iteration   3: 3.894 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.968 ±(99.9%) 1.245 ms/op [Average]
  (min, avg, max) = (3.894, 3.968, 4.028), stdev = 0.068
  CI (99.9%): [2.723, 5.213] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 8.666 ±(99.9%) 0.114 ms/op
# Warmup Iteration   2: 3.906 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.604 ±(99.9%) 0.011 ms/op
Iteration   1: 3.425 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.616 ms/op
                 createUser·p0.50:   3.363 ms/op
                 createUser·p0.90:   3.785 ms/op
                 createUser·p0.95:   4.227 ms/op
                 createUser·p0.99:   5.997 ms/op
                 createUser·p0.999:  20.581 ms/op
                 createUser·p0.9999: 23.953 ms/op
                 createUser·p1.00:   25.297 ms/op

Iteration   2: 3.365 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.575 ms/op
                 createUser·p0.50:   3.244 ms/op
                 createUser·p0.90:   3.727 ms/op
                 createUser·p0.95:   4.010 ms/op
                 createUser·p0.99:   6.137 ms/op
                 createUser·p0.999:  23.233 ms/op
                 createUser·p0.9999: 27.165 ms/op
                 createUser·p1.00:   29.393 ms/op

Iteration   3: 3.374 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.722 ms/op
                 createUser·p0.50:   3.359 ms/op
                 createUser·p0.90:   3.662 ms/op
                 createUser·p0.95:   3.917 ms/op
                 createUser·p0.99:   5.349 ms/op
                 createUser·p0.999:  19.779 ms/op
                 createUser·p0.9999: 26.345 ms/op
                 createUser·p1.00:   27.001 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 283261
  mean =      3.388 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12858 
    [ 2.500,  5.000) = 264854 
    [ 5.000,  7.500) = 4366 
    [ 7.500, 10.000) = 506 
    [10.000, 12.500) = 237 
    [12.500, 15.000) = 81 
    [15.000, 17.500) = 40 
    [17.500, 20.000) = 40 
    [20.000, 22.500) = 93 
    [22.500, 25.000) = 108 
    [25.000, 27.500) = 71 

  Percentiles, ms/op:
      p(0.0000) =      1.575 ms/op
     p(50.0000) =      3.338 ms/op
     p(90.0000) =      3.715 ms/op
     p(95.0000) =      4.047 ms/op
     p(99.0000) =      5.890 ms/op
     p(99.9000) =     19.947 ms/op
     p(99.9900) =     26.378 ms/op
     p(99.9990) =     29.240 ms/op
     p(99.9999) =     29.393 ms/op
    p(100.0000) =     29.393 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 8.911 ±(99.9%) 0.128 ms/op
# Warmup Iteration   2: 3.612 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.277 ±(99.9%) 0.007 ms/op
Iteration   1: 3.312 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.655 ms/op
                 existUser·p0.50:   3.305 ms/op
                 existUser·p0.90:   3.502 ms/op
                 existUser·p0.95:   4.051 ms/op
                 existUser·p0.99:   5.631 ms/op
                 existUser·p0.999:  10.198 ms/op
                 existUser·p0.9999: 24.751 ms/op
                 existUser·p1.00:   26.804 ms/op

Iteration   2: 3.282 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.575 ms/op
                 existUser·p0.50:   3.219 ms/op
                 existUser·p0.90:   3.711 ms/op
                 existUser·p0.95:   3.990 ms/op
                 existUser·p0.99:   5.366 ms/op
                 existUser·p0.999:  15.333 ms/op
                 existUser·p0.9999: 23.667 ms/op
                 existUser·p1.00:   24.117 ms/op

Iteration   3: 3.307 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.417 ms/op
                 existUser·p0.50:   3.187 ms/op
                 existUser·p0.90:   3.576 ms/op
                 existUser·p0.95:   3.994 ms/op
                 existUser·p0.99:   6.266 ms/op
                 existUser·p0.999:  17.303 ms/op
                 existUser·p0.9999: 25.972 ms/op
                 existUser·p1.00:   27.329 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 290711
  mean =      3.300 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15897 
    [ 2.500,  5.000) = 268710 
    [ 5.000,  7.500) = 5027 
    [ 7.500, 10.000) = 413 
    [10.000, 12.500) = 318 
    [12.500, 15.000) = 68 
    [15.000, 17.500) = 22 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 43 
    [22.500, 25.000) = 143 
    [25.000, 27.500) = 38 

  Percentiles, ms/op:
      p(0.0000) =      1.417 ms/op
     p(50.0000) =      3.240 ms/op
     p(90.0000) =      3.600 ms/op
     p(95.0000) =      4.006 ms/op
     p(99.0000) =      5.669 ms/op
     p(99.9000) =     14.715 ms/op
     p(99.9900) =     25.100 ms/op
     p(99.9990) =     26.813 ms/op
     p(99.9999) =     27.329 ms/op
    p(100.0000) =     27.329 ms/op


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
# Warmup Iteration   1: 7.885 ±(99.9%) 0.110 ms/op
# Warmup Iteration   2: 3.759 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.479 ±(99.9%) 0.010 ms/op
Iteration   1: 3.406 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.712 ms/op
                 getUser·p0.50:   3.248 ms/op
                 getUser·p0.90:   3.891 ms/op
                 getUser·p0.95:   4.235 ms/op
                 getUser·p0.99:   5.981 ms/op
                 getUser·p0.999:  21.989 ms/op
                 getUser·p0.9999: 28.141 ms/op
                 getUser·p1.00:   31.883 ms/op

Iteration   2: 3.465 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.581 ms/op
                 getUser·p0.50:   3.346 ms/op
                 getUser·p0.90:   3.785 ms/op
                 getUser·p0.95:   3.990 ms/op
                 getUser·p0.99:   6.005 ms/op
                 getUser·p0.999:  23.785 ms/op
                 getUser·p0.9999: 26.870 ms/op
                 getUser·p1.00:   27.296 ms/op

Iteration   3: 3.497 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.485 ms/op
                 getUser·p0.50:   3.330 ms/op
                 getUser·p0.90:   3.883 ms/op
                 getUser·p0.95:   4.375 ms/op
                 getUser·p0.99:   6.701 ms/op
                 getUser·p0.999:  19.342 ms/op
                 getUser·p0.9999: 26.477 ms/op
                 getUser·p1.00:   27.263 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 277659
  mean =      3.456 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4655 
    [ 2.500,  5.000) = 264843 
    [ 5.000,  7.500) = 6744 
    [ 7.500, 10.000) = 825 
    [10.000, 12.500) = 229 
    [12.500, 15.000) = 64 
    [15.000, 17.500) = 10 
    [17.500, 20.000) = 18 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 125 
    [25.000, 27.500) = 97 
    [27.500, 30.000) = 12 
    [30.000, 32.500) = 7 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.485 ms/op
     p(50.0000) =      3.305 ms/op
     p(90.0000) =      3.842 ms/op
     p(95.0000) =      4.182 ms/op
     p(99.0000) =      6.283 ms/op
     p(99.9000) =     19.760 ms/op
     p(99.9900) =     27.132 ms/op
     p(99.9990) =     31.293 ms/op
     p(99.9999) =     31.883 ms/op
    p(100.0000) =     31.883 ms/op


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
# Warmup Iteration   1: 10.416 ±(99.9%) 0.144 ms/op
# Warmup Iteration   2: 4.509 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.058 ±(99.9%) 0.013 ms/op
Iteration   1: 4.066 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.599 ms/op
                 listUser·p0.50:   3.912 ms/op
                 listUser·p0.90:   4.596 ms/op
                 listUser·p0.95:   5.063 ms/op
                 listUser·p0.99:   7.856 ms/op
                 listUser·p0.999:  18.743 ms/op
                 listUser·p0.9999: 25.403 ms/op
                 listUser·p1.00:   25.854 ms/op

Iteration   2: 4.131 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.690 ms/op
                 listUser·p0.50:   4.014 ms/op
                 listUser·p0.90:   4.653 ms/op
                 listUser·p0.95:   4.997 ms/op
                 listUser·p0.99:   7.406 ms/op
                 listUser·p0.999:  16.376 ms/op
                 listUser·p0.9999: 21.668 ms/op
                 listUser·p1.00:   21.791 ms/op

Iteration   3: 3.943 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.913 ms/op
                 listUser·p0.50:   3.817 ms/op
                 listUser·p0.90:   4.334 ms/op
                 listUser·p0.95:   4.555 ms/op
                 listUser·p0.99:   6.898 ms/op
                 listUser·p0.999:  15.870 ms/op
                 listUser·p0.9999: 17.228 ms/op
                 listUser·p1.00:   17.400 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 237486
  mean =      4.045 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 29 
    [ 2.500,  5.000) = 227301 
    [ 5.000,  7.500) = 7818 
    [ 7.500, 10.000) = 1523 
    [10.000, 12.500) = 275 
    [12.500, 15.000) = 142 
    [15.000, 17.500) = 220 
    [17.500, 20.000) = 78 
    [20.000, 22.500) = 47 
    [22.500, 25.000) = 40 
    [25.000, 27.500) = 13 

  Percentiles, ms/op:
      p(0.0000) =      1.599 ms/op
     p(50.0000) =      3.908 ms/op
     p(90.0000) =      4.514 ms/op
     p(95.0000) =      4.882 ms/op
     p(99.0000) =      7.447 ms/op
     p(99.9000) =     16.589 ms/op
     p(99.9900) =     23.536 ms/op
     p(99.9990) =     25.784 ms/op
     p(99.9999) =     25.854 ms/op
    p(100.0000) =     25.854 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.269 ± 4.623  ops/ms
ClientPb.existUser                       thrpt       3   9.897 ± 2.893  ops/ms
ClientPb.getUser                         thrpt       3   9.338 ± 2.100  ops/ms
ClientPb.listUser                        thrpt       3   8.023 ± 3.933  ops/ms
ClientPb.createUser                       avgt       3   3.398 ± 1.164   ms/op
ClientPb.existUser                        avgt       3   3.338 ± 1.348   ms/op
ClientPb.getUser                          avgt       3   3.384 ± 1.927   ms/op
ClientPb.listUser                         avgt       3   3.968 ± 1.245   ms/op
ClientPb.createUser                     sample  283261   3.388 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.575           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.338           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.715           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.047           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.890           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.947           ms/op
ClientPb.createUser:createUser·p0.9999  sample          26.378           ms/op
ClientPb.createUser:createUser·p1.00    sample          29.393           ms/op
ClientPb.existUser                      sample  290711   3.300 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.417           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.240           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.600           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.006           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.669           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.715           ms/op
ClientPb.existUser:existUser·p0.9999    sample          25.100           ms/op
ClientPb.existUser:existUser·p1.00      sample          27.329           ms/op
ClientPb.getUser                        sample  277659   3.456 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.485           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.305           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.842           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.182           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.283           ms/op
ClientPb.getUser:getUser·p0.999         sample          19.760           ms/op
ClientPb.getUser:getUser·p0.9999        sample          27.132           ms/op
ClientPb.getUser:getUser·p1.00          sample          31.883           ms/op
ClientPb.listUser                       sample  237486   4.045 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.599           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.908           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.514           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.882           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.447           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.589           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.536           ms/op
ClientPb.listUser:listUser·p1.00        sample          25.854           ms/op
