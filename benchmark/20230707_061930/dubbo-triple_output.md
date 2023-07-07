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
# Warmup Iteration   1: 2.424 ops/ms
# Warmup Iteration   2: 5.771 ops/ms
# Warmup Iteration   3: 9.098 ops/ms
Iteration   1: 10.042 ops/ms
Iteration   2: 9.839 ops/ms
Iteration   3: 9.856 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.912 ±(99.9%) 2.046 ops/ms [Average]
  (min, avg, max) = (9.839, 9.912, 10.042), stdev = 0.112
  CI (99.9%): [7.866, 11.959] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 3.510 ops/ms
# Warmup Iteration   2: 9.223 ops/ms
# Warmup Iteration   3: 9.923 ops/ms
Iteration   1: 10.544 ops/ms
Iteration   2: 10.365 ops/ms
Iteration   3: 10.608 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.506 ±(99.9%) 2.297 ops/ms [Average]
  (min, avg, max) = (10.365, 10.506, 10.608), stdev = 0.126
  CI (99.9%): [8.209, 12.803] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.243 ops/ms
# Warmup Iteration   2: 8.864 ops/ms
# Warmup Iteration   3: 9.792 ops/ms
Iteration   1: 9.780 ops/ms
Iteration   2: 10.175 ops/ms
Iteration   3: 10.022 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.992 ±(99.9%) 3.634 ops/ms [Average]
  (min, avg, max) = (9.780, 9.992, 10.175), stdev = 0.199
  CI (99.9%): [6.359, 13.626] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 3.051 ops/ms
# Warmup Iteration   2: 7.897 ops/ms
# Warmup Iteration   3: 8.304 ops/ms
Iteration   1: 8.503 ops/ms
Iteration   2: 8.467 ops/ms
Iteration   3: 8.553 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.507 ±(99.9%) 0.791 ops/ms [Average]
  (min, avg, max) = (8.467, 8.507, 8.553), stdev = 0.043
  CI (99.9%): [7.717, 9.298] (assumes normal distribution)


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
# Warmup Iteration   1: 8.211 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.489 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.280 ±(99.9%) 0.006 ms/op
Iteration   1: 3.250 ±(99.9%) 0.008 ms/op
Iteration   2: 3.280 ±(99.9%) 0.007 ms/op
Iteration   3: 3.157 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.229 ±(99.9%) 1.166 ms/op [Average]
  (min, avg, max) = (3.157, 3.229, 3.280), stdev = 0.064
  CI (99.9%): [2.062, 4.395] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 7.710 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.465 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.317 ±(99.9%) 0.006 ms/op
Iteration   1: 3.133 ±(99.9%) 0.005 ms/op
Iteration   2: 3.186 ±(99.9%) 0.003 ms/op
Iteration   3: 3.175 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.165 ±(99.9%) 0.509 ms/op [Average]
  (min, avg, max) = (3.133, 3.165, 3.186), stdev = 0.028
  CI (99.9%): [2.656, 3.674] (assumes normal distribution)


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
# Warmup Iteration   1: 8.935 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.716 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.377 ±(99.9%) 0.002 ms/op
Iteration   1: 3.385 ±(99.9%) 0.007 ms/op
Iteration   2: 3.229 ±(99.9%) 0.003 ms/op
Iteration   3: 3.231 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.281 ±(99.9%) 1.638 ms/op [Average]
  (min, avg, max) = (3.229, 3.281, 3.385), stdev = 0.090
  CI (99.9%): [1.643, 4.920] (assumes normal distribution)


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
# Warmup Iteration   1: 8.693 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 4.040 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.892 ±(99.9%) 0.004 ms/op
Iteration   1: 3.832 ±(99.9%) 0.007 ms/op
Iteration   2: 3.714 ±(99.9%) 0.010 ms/op
Iteration   3: 3.821 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.789 ±(99.9%) 1.188 ms/op [Average]
  (min, avg, max) = (3.714, 3.789, 3.832), stdev = 0.065
  CI (99.9%): [2.601, 4.977] (assumes normal distribution)


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
# Warmup Iteration   1: 8.901 ±(99.9%) 0.110 ms/op
# Warmup Iteration   2: 3.864 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.337 ±(99.9%) 0.010 ms/op
Iteration   1: 3.267 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.143 ms/op
                 createUser·p0.50:   3.191 ms/op
                 createUser·p0.90:   3.625 ms/op
                 createUser·p0.95:   4.039 ms/op
                 createUser·p0.99:   5.798 ms/op
                 createUser·p0.999:  17.203 ms/op
                 createUser·p0.9999: 22.696 ms/op
                 createUser·p1.00:   23.593 ms/op

Iteration   2: 3.198 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.266 ms/op
                 createUser·p0.50:   3.154 ms/op
                 createUser·p0.90:   3.514 ms/op
                 createUser·p0.95:   3.740 ms/op
                 createUser·p0.99:   5.292 ms/op
                 createUser·p0.999:  17.305 ms/op
                 createUser·p0.9999: 23.724 ms/op
                 createUser·p1.00:   24.084 ms/op

Iteration   3: 3.419 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.272 ms/op
                 createUser·p0.50:   3.387 ms/op
                 createUser·p0.90:   3.899 ms/op
                 createUser·p0.95:   4.186 ms/op
                 createUser·p0.99:   5.382 ms/op
                 createUser·p0.999:  14.145 ms/op
                 createUser·p0.9999: 19.375 ms/op
                 createUser·p1.00:   20.808 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 291489
  mean =      3.292 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14785 
    [ 2.500,  5.000) = 271496 
    [ 5.000,  7.500) = 4388 
    [ 7.500, 10.000) = 407 
    [10.000, 12.500) = 31 
    [12.500, 15.000) = 46 
    [15.000, 17.500) = 130 
    [17.500, 20.000) = 74 
    [20.000, 22.500) = 55 
    [22.500, 25.000) = 77 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.143 ms/op
     p(50.0000) =      3.219 ms/op
     p(90.0000) =      3.715 ms/op
     p(95.0000) =      4.014 ms/op
     p(99.0000) =      5.530 ms/op
     p(99.9000) =     15.909 ms/op
     p(99.9900) =     23.457 ms/op
     p(99.9990) =     23.888 ms/op
     p(99.9999) =     24.084 ms/op
    p(100.0000) =     24.084 ms/op


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
# Warmup Iteration   1: 7.268 ±(99.9%) 0.079 ms/op
# Warmup Iteration   2: 3.357 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.295 ±(99.9%) 0.008 ms/op
Iteration   1: 3.096 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.055 ms/op
                 existUser·p0.50:   3.113 ms/op
                 existUser·p0.90:   3.297 ms/op
                 existUser·p0.95:   3.527 ms/op
                 existUser·p0.99:   5.186 ms/op
                 existUser·p0.999:  10.240 ms/op
                 existUser·p0.9999: 18.907 ms/op
                 existUser·p1.00:   19.366 ms/op

Iteration   2: 3.172 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.182 ms/op
                 existUser·p0.50:   3.129 ms/op
                 existUser·p0.90:   3.469 ms/op
                 existUser·p0.95:   3.899 ms/op
                 existUser·p0.99:   5.849 ms/op
                 existUser·p0.999:  10.882 ms/op
                 existUser·p0.9999: 22.113 ms/op
                 existUser·p1.00:   23.298 ms/op

Iteration   3: 3.040 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   1.503 ms/op
                 existUser·p0.50:   2.966 ms/op
                 existUser·p0.90:   3.269 ms/op
                 existUser·p0.95:   3.441 ms/op
                 existUser·p0.99:   5.308 ms/op
                 existUser·p0.999:  9.762 ms/op
                 existUser·p0.9999: 20.398 ms/op
                 existUser·p1.00:   20.906 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 309170
  mean =      3.102 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24038 
    [ 2.500,  5.000) = 279909 
    [ 5.000,  7.500) = 4385 
    [ 7.500, 10.000) = 475 
    [10.000, 12.500) = 74 
    [12.500, 15.000) = 26 
    [15.000, 17.500) = 65 
    [17.500, 20.000) = 152 
    [20.000, 22.500) = 38 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.055 ms/op
     p(50.0000) =      3.076 ms/op
     p(90.0000) =      3.314 ms/op
     p(95.0000) =      3.600 ms/op
     p(99.0000) =      5.415 ms/op
     p(99.9000) =     10.680 ms/op
     p(99.9900) =     20.906 ms/op
     p(99.9990) =     23.086 ms/op
     p(99.9999) =     23.298 ms/op
    p(100.0000) =     23.298 ms/op


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
# Warmup Iteration   1: 8.575 ±(99.9%) 0.099 ms/op
# Warmup Iteration   2: 3.496 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.291 ±(99.9%) 0.010 ms/op
Iteration   1: 3.173 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.298 ms/op
                 getUser·p0.50:   3.068 ms/op
                 getUser·p0.90:   3.441 ms/op
                 getUser·p0.95:   3.682 ms/op
                 getUser·p0.99:   5.898 ms/op
                 getUser·p0.999:  15.270 ms/op
                 getUser·p0.9999: 20.504 ms/op
                 getUser·p1.00:   21.365 ms/op

Iteration   2: 3.366 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.620 ms/op
                 getUser·p0.50:   3.232 ms/op
                 getUser·p0.90:   4.170 ms/op
                 getUser·p0.95:   4.661 ms/op
                 getUser·p0.99:   6.226 ms/op
                 getUser·p0.999:  17.991 ms/op
                 getUser·p0.9999: 22.053 ms/op
                 getUser·p1.00:   25.428 ms/op

Iteration   3: 3.187 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.384 ms/op
                 getUser·p0.50:   3.080 ms/op
                 getUser·p0.90:   3.465 ms/op
                 getUser·p0.95:   3.670 ms/op
                 getUser·p0.99:   5.546 ms/op
                 getUser·p0.999:  15.291 ms/op
                 getUser·p0.9999: 24.640 ms/op
                 getUser·p1.00:   26.116 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 296170
  mean =      3.240 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10209 
    [ 2.500,  5.000) = 279518 
    [ 5.000,  7.500) = 5288 
    [ 7.500, 10.000) = 712 
    [10.000, 12.500) = 27 
    [12.500, 15.000) = 109 
    [15.000, 17.500) = 34 
    [17.500, 20.000) = 188 
    [20.000, 22.500) = 47 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 10 

  Percentiles, ms/op:
      p(0.0000) =      1.298 ms/op
     p(50.0000) =      3.105 ms/op
     p(90.0000) =      3.609 ms/op
     p(95.0000) =      4.194 ms/op
     p(99.0000) =      5.874 ms/op
     p(99.9000) =     15.270 ms/op
     p(99.9900) =     23.573 ms/op
     p(99.9990) =     25.609 ms/op
     p(99.9999) =     26.116 ms/op
    p(100.0000) =     26.116 ms/op


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
# Warmup Iteration   1: 8.747 ±(99.9%) 0.119 ms/op
# Warmup Iteration   2: 4.184 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.829 ±(99.9%) 0.013 ms/op
Iteration   1: 3.843 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.288 ms/op
                 listUser·p0.50:   3.678 ms/op
                 listUser·p0.90:   4.194 ms/op
                 listUser·p0.95:   4.481 ms/op
                 listUser·p0.99:   7.774 ms/op
                 listUser·p0.999:  17.635 ms/op
                 listUser·p0.9999: 24.904 ms/op
                 listUser·p1.00:   25.657 ms/op

Iteration   2: 3.792 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.175 ms/op
                 listUser·p0.50:   3.658 ms/op
                 listUser·p0.90:   4.096 ms/op
                 listUser·p0.95:   4.293 ms/op
                 listUser·p0.99:   7.160 ms/op
                 listUser·p0.999:  14.320 ms/op
                 listUser·p0.9999: 17.803 ms/op
                 listUser·p1.00:   19.038 ms/op

Iteration   3: 3.697 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.739 ms/op
                 listUser·p0.50:   3.596 ms/op
                 listUser·p0.90:   3.944 ms/op
                 listUser·p0.95:   4.153 ms/op
                 listUser·p0.99:   6.880 ms/op
                 listUser·p0.999:  12.878 ms/op
                 listUser·p0.9999: 16.843 ms/op
                 listUser·p1.00:   16.908 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 253997
  mean =      3.777 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 53 
    [ 2.500,  5.000) = 246648 
    [ 5.000,  7.500) = 4969 
    [ 7.500, 10.000) = 1677 
    [10.000, 12.500) = 228 
    [12.500, 15.000) = 194 
    [15.000, 17.500) = 121 
    [17.500, 20.000) = 63 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 26 
    [25.000, 27.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      0.739 ms/op
     p(50.0000) =      3.633 ms/op
     p(90.0000) =      4.100 ms/op
     p(95.0000) =      4.317 ms/op
     p(99.0000) =      7.332 ms/op
     p(99.9000) =     14.352 ms/op
     p(99.9900) =     22.984 ms/op
     p(99.9990) =     25.329 ms/op
     p(99.9999) =     25.657 ms/op
    p(100.0000) =     25.657 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.912 ± 2.046  ops/ms
ClientPb.existUser                       thrpt       3  10.506 ± 2.297  ops/ms
ClientPb.getUser                         thrpt       3   9.992 ± 3.634  ops/ms
ClientPb.listUser                        thrpt       3   8.507 ± 0.791  ops/ms
ClientPb.createUser                       avgt       3   3.229 ± 1.166   ms/op
ClientPb.existUser                        avgt       3   3.165 ± 0.509   ms/op
ClientPb.getUser                          avgt       3   3.281 ± 1.638   ms/op
ClientPb.listUser                         avgt       3   3.789 ± 1.188   ms/op
ClientPb.createUser                     sample  291489   3.292 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.143           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.219           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.715           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.014           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.530           ms/op
ClientPb.createUser:createUser·p0.999   sample          15.909           ms/op
ClientPb.createUser:createUser·p0.9999  sample          23.457           ms/op
ClientPb.createUser:createUser·p1.00    sample          24.084           ms/op
ClientPb.existUser                      sample  309170   3.102 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.055           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.076           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.314           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.600           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.415           ms/op
ClientPb.existUser:existUser·p0.999     sample          10.680           ms/op
ClientPb.existUser:existUser·p0.9999    sample          20.906           ms/op
ClientPb.existUser:existUser·p1.00      sample          23.298           ms/op
ClientPb.getUser                        sample  296170   3.240 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.298           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.105           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.609           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.194           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.874           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.270           ms/op
ClientPb.getUser:getUser·p0.9999        sample          23.573           ms/op
ClientPb.getUser:getUser·p1.00          sample          26.116           ms/op
ClientPb.listUser                       sample  253997   3.777 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.739           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.633           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.100           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.317           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.332           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.352           ms/op
ClientPb.listUser:listUser·p0.9999      sample          22.984           ms/op
ClientPb.listUser:listUser·p1.00        sample          25.657           ms/op
